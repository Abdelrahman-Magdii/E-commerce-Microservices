FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/product-0.0.1-SNAPSHOT.jar /app/app.jar

EXPOSE 8050

ENTRYPOINT ["java","-jar","app.jar"]