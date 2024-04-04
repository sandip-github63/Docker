# Use the official OpenJDK image as the base image
FROM openjdk:8-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the Java application JAR file into the container at /app
COPY HelloWorld.java .

# Compile the Java application
RUN javac HelloWorld.java

# Define the command to run the Java application when the container starts
CMD ["java", "HelloWorld"]
