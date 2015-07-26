# AWS Elastc Beanstalk Spring Boot Template
This is Java Spring Boot project template for the AWS Elastic Beanstalk Web Server Tier.
By configure the POM file, this project can run in Tomcat 8 container as WAR file or can run as standalone executable JAR file.


## How to Compile
1. Read and edit the POM file to choose your prefered package. (Executable JAR is the default.)
2. mvn package
3. Now you have the compiled target package


## Test Run
* Executable JAR
    1. java -jar target/gs-messaging-stomp-websocket-0.1.0.jar
    2. open http://localhost:8080/
* WAR in Tomcat 8
    1. deploy WAR onto Tomcat 8 (your own or AWS Elastic Beanstalk)
    2. open http://localhost:8080/gs-messaging-stomp-websocket-0.1.0/


## Have Fun :)


