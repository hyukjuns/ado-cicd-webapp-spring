# demo spring-boot web application
스프링 부트 데모 웹 어플리케이션

# Spring Initailizer
- Maven Project
- Java Version: 8 (OpenJDK 1.8)
- Spring Boot: 2.4.5
- Packaging: War
- Dependancies   
    - Spring Web
    - Thymeleaf
    - Spring Boot DevTools
# Server side
- Tomcat 9.0
# Run
### mvnw
```
mvnw spring-boot:run
```
### war
```
java -jar <WARFILE>.war
```
# Build
```
mvnw package
```
# Java Command
Compile -> .class
```
javac <JAVAFILE>.java
```
Excuting Class
```
java <ClassName>
```
Excuting JAR or WAR
```
java -jar <FILENAME>.jar or <FILENAME>.war 
```
### Reference
[Spring GetStarted](https://spring.io/guides/gs/serving-web-content/)
 
