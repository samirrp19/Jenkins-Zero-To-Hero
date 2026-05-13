# Use Java 17 runtime image
FROM eclipse-temurin:17-jre-alpine

# Application JAR path
ARG JAR_FILE=target/spring-boot-web.jar

# Create app directory
WORKDIR /opt/app

# Copy JAR file into container
COPY ${JAR_FILE} app.jar

# Expose application port
EXPOSE 7000

# Run application
ENTRYPOINT ["java", "-jar", "app.jar"]
