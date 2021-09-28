# fargateSpringActuator

Example using spring boot actuator health check with Fargate cluster on AWS configured to use a custom path for health check monitoring /actuator/health

- prerequisites: Java JDK (Open15), docker, copilot
- usage: checkout and run copilot init
- test locally: ./mvnw spring-boot:run          
- configure custom health check: check [/copilot/springapp/manifest.yml](https://github.com/sercasti/fargateSpringActuator/blob/main/copilot/springapp/manifest.yml)
