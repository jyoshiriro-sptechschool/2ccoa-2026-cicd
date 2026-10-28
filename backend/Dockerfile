FROM eclipse-temurin:21-jre

WORKDIR /app

COPY target/api-pets.jar /app/api-pets.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "/app/api-pets.jar"]
