# Base image from Oracle Container Registry
FROM container-registry.oracle.com/java/jdk:17

WORKDIR /app

COPY target/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
