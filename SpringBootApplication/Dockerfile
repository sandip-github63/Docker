# Use a base image with Java 8 installed
FROM openjdk:8-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JUnit Testing application jar file into the container
COPY JunitTestingApp.jar /app

# Expose any necessary ports (if your app requires)
EXPOSE 8085

# Command to run the JUnit Testing application when the container starts
CMD ["java", "-jar", "JunitTestingApp.jar"]






