FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/notification-0.0.1-SNAPSHOT.jar /app/app.jar

EXPOSE 8040

ENTRYPOINT ["java","-jar","app.jar"]