# Use OpenJDK as base
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy built JAR (adjust name if needed)
COPY target/*.jar app.jar

# Expose port (adjust if your app uses a different port)
EXPOSE 2025 

# Run the app
ENTRYPOINT ["java", "-jar", "app.jar"]

