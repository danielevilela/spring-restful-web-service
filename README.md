# spring-restful-web-service
Simple "hello world" RESTful web service with Spring.

## Instructions
Using Maven, you can run the application using: 
```
mvn spring-boot:run
```

It will accept HTTP GET requests at:

http://localhost:8080/greeting

and respond with a JSON representation of a greeting:
```json
{"id":1,"content":"Hello, World!"}
```

You can customize the greeting with an optional name parameter in the query string:

http://localhost:8080/greeting?name=Dani

The name parameter value overrides the default value of "World" and is reflected in the response:
```json
{"id":1,"content":"Hello, Dani!"}
```
