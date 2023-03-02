# Eureka Server learning application 

All you need to create Eureka server is @EnableEurekaServer annotation on your Spring Boot Application

## Configuration

- port: 8761 - this is a standard one
- registerWithEureka: false - because we don't need to register the Eureka Server with itself
- fetchRegistry: false - because we don't need local copy of registry, we are registry

## Dashboard

Dashboard is enabled by default. To see you need to go to the application's uri:

http://localhost:8761/