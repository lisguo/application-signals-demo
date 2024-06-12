# Use Windows base image
FROM winamd64/openjdk:11-nanoserver-1809

# everything will be installed inside this directory inside the container
WORKDIR "C:/ProgramData"

ADD ./target/spring-petclinic-api-gateway-2.6.7.jar "C:/ProgramData"

# Expose the port your app runs on
EXPOSE 8080

# Command to run the application
CMD ["java", "-jar", "C:/ProgramData/spring-petclinic-api-gateway-2.6.7.jar"]