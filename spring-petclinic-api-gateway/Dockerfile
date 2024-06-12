# Use Windows base image
FROM mcr.microsoft.com/windows/servercore:ltsc2019

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container
COPY ./target/spring-petclinic-api-gateway-2.6.7.jar /app

# Expose the port your app runs on
EXPOSE 8080

# Command to run the application
CMD ["java", "-jar", "spring-petclinic-api-gateway-2.6.7.jar"]
