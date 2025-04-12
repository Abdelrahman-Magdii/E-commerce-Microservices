FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/gateway-0.0.1-SNAPSHOT.jar /app/app.jar

EXPOSE 8222

ENTRYPOINT ["java","-jar","app.jar"]