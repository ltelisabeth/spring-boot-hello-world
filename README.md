# spring-boot-hello-world

Step 1 — Create Spring boot project
by heading over to the spring initializer at https://start.spring.io/

Step 2 — Import project to IDE

Step 3 — Creating our REST Endpoint
The @RESTController is a spring boot annotation that informs our application that our HelloWorldController class will be exposing REST endpoints. This will help us create RESTful web services.
Similarly, the @GetMapping annotation is used to handle HTTP GET requests. GET requests are used to retrieve sources. The “/hello-world” is the URI needed to gain access to the source.

Step 4 — Test our HelloWorld endpoint
By default, Spring boot makes the tomcat server running on port 8080. 
Next, open your browser and enter the following URL: http://localhost:8080/hello-world. You should see the “Hello World” message on your browser:
![image](https://user-images.githubusercontent.com/52229965/176809615-bba93295-3dae-4165-b273-c1dfc7d0a376.png)

References: https://medium.com/@ismailvohra/how-to-create-a-simple-hello-world-rest-api-in-spring-boot-a89e75cbb48b
