# demo spring-boot web application
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
```aidl
mvnw spring-boot:run
```
### war
```aidl
java -jar <WARFILE>.war
```
# Build
```aidl
mvnw package
```
# Java Command
Compile -> .class
```aidl
javac <JAVAFILE>.java
```
Excuting Class
```aidl
java <ClassName>
```
Excuting JAR or WAR
```aidl
java -jar <FILENAME>.jar or <FILENAME>.war 
```
### Reference
[Spring GetStarted](https://spring.io/guides/gs/serving-web-content/)
 