FROM eclipse-temurin:17-jre-alpine

WORKDIR /opt/app

COPY target/*.jar app.jar

EXPOSE 7000

ENTRYPOINT ["java", "-jar", "app.jar"]
