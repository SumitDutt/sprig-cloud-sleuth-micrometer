# sprig-cloud-sleuth-micrometer 
https://zipkin.io/pages/quickstart.html
java -jar zipkin-server-3.4.4-exec.jar 

http://127.0.0.1:9411/zipkin/

#Zipkin
management.tracing.sampling.probablity=1.0  
#management.zipkin.tracing.endpoint=


		<!-- Zipki Miceometer-->
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-actuator</artifactId>
		</dependency>
		<dependency>
			<groupId>io.micrometer</groupId>
			<artifactId>micrometer-tracing-bridge-brave</artifactId>
		</dependency>
		<dependency>
			<groupId>io.zipkin.reporter2</groupId>
			<artifactId>zipkin-reporter-brave</artifactId>
		</dependency>
		<dependency>
			<groupId>io.github.openfeign</groupId>
			<artifactId>feign-micrometer</artifactId>
		</dependency>
