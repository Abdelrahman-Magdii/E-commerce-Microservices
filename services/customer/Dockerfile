FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/customer-0.0.1-SNAPSHOT.jar /app/app.jar

EXPOSE 8090

ENTRYPOINT ["java","-jar","app.jar"]