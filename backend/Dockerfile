FROM openjdk:17-jdk-slim

WORKDIR /opt/project

COPY ./backend ./

EXPOSE 8080

CMD ["java", "-jar", "/opt/project/target/WEB_SPRING-0.0.1-SNAPSHOT.jar"]