FROM openjdk:11

COPY target/spring-boot-docker-app.jar  /usr/app/

WORKDIR /usr/app/

EXPPOSE 8080

ENTRYPOINT ["java", "-jar", "spring-boot-docker-app.jar"]
