# Spring app with a simple MVC

### About
A simple Spring application that has a static home page and that will also 
accept HTTP GET requests at: http://localhost:8080/greeting.

It will respond with a web page containing a greeting: “Hello, World!”

You can customize the greeting with an optional name parameter in the query 
string. The URL might then be http://localhost:8080/greeting?name=User.

### Techstack
* Java 11
* Spring Boot : 2.4.4
* Spring WEB
* Spring Boot DevTools 
* Thymeleaf 
* Maven Wrapper
* Spring Initializer : https://start.spring.io/
* Tomcat

### Usage
```sh
./mvnw spring-boot:run
```

The service is active then on : http://localhost:8080/greeting

---

based on:

* https://spring.io/guides/gs/serving-web-content/
* https://start.spring.io/