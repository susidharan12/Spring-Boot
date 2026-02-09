# Use Java 21 inside the container (Eclipse Temurin is official and available)
FROM eclipse-temurin:21-jdk

# Set working directory
WORKDIR /app

# Copy the compiled jar from target folder
COPY target/*.jar app.jar

# Run the jar
ENTRYPOINT ["java", "-jar", "app.jar"]
