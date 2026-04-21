FROM eclipse-temurin:17-jre-alpine
WORKDIR /app
COPY target/myapp.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
