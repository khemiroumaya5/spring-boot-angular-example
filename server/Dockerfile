# Dockerfile backend
FROM eclipse-temurin:11-jdk

# Copier le JAR compilé dans l'image
COPY target/*.jar app.jar

# Exposer le port de l'application
EXPOSE 8080

# Lancer l'application
ENTRYPOINT ["java", "-jar", "/app.jar"]

