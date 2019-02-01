FROM openjdk:alpine
MAINTAINER Wellington Costa <wellington.costa128@gmail.com>
ADD target/reservation-service.jar reservation-service.jar
ENTRYPOINT ["java", "-jar", "/reservation-service.jar"]
EXPOSE 3000