# admin-ui
This is a simple Spring boot Admin application.

To run the application:

0- Pre-requisites
```
You'll need Java 11 and Maven 3 installed
```

1- To run the test ( by default in a random port)
```
mvn clean test
```

2- To run the application (by default in port 7070)
 ```
mvn spring-boot:run
```

If you wantt to access the Springboot Admin UI, go to http://localhost:7070/wallboard

Actuator runs in port 10090 in case you want to take a look to the metrics