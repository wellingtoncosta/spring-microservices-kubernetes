FROM openjdk:alpine
MAINTAINER Wellington Costa <wellington.costa128@gmail.com>
ADD target/client-service.jar client-service.jar
ENTRYPOINT ["java", "-jar", "/client-service.jar"]
EXPOSE 2000