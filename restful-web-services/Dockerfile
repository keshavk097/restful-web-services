# Use the official Eclipse Temurin base image with Java 17
FROM eclipse-temurin:17-jre

# Set the working directory in the container
WORKDIR /app

# Copy the built jar file from the target directory to the container
COPY target/restful-web-services-0.0.1-SNAPSHOT.jar app.jar

# Expose the port your application will run on
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]
