FROM eclipse-temurin:21-jdk
WORKDIR /app
COPY build/libs/lab4backend.jar app.jar
EXPOSE 8000
ENTRYPOINT ["java", "-jar", "app.jar"]