# Use an official OpenJDK 8 runtime as a parent image
FROM openjdk:8-jre-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the packaged JAR file into the container at /app
COPY app.jar /app/

# Expose port 8080 to the outside world
EXPOSE 8080

# Specify the command to run on container start
CMD ["java", "-jar", "app.jar"]
