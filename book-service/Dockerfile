FROM openjdk:alpine
MAINTAINER Wellington Costa <wellington.costa128@gmail.com>
ADD target/book-service.jar book-service.jar
ENTRYPOINT ["java", "-jar", "/book-service.jar"]
EXPOSE 1000