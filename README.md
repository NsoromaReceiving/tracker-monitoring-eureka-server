# Tracker Monitoring Eureka Server #

## Quick summary ##

This application serves as spring cloud eureka server to clients

* [Eureka-Server] (https://banabasave@bitbucket.org/banabasave/tracker-monitoring-scheduler.git) 
* [nsoroma-tracker-monitoring-service] (https://banabasave@bitbucket.org/hawkmanlabs/nsoroma-tracker-monitoring-service.git)

It uses [Spring Boot](http://projects.spring.io/spring-boot/) to start Spring context and run the application and [Spring Cloud Eureka](https://cloud.spring.io/spring-cloud-netflix/) to integrate Netflix implementation into Spring.

##Version

* Spring Boot 2.1.8
* Spring Cloud 1.1.8



### Execution instructions ###

The application starts as a normal Spring Boot application:

* Run `mvn clean spring-boot:run` inside the project