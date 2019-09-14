FROM openjdk:latest

# Add Maintainer Info
LABEL maintainer="alagappan.ramasamy@cognizant.com"


ADD target/ModEurekaServer.jar ModEurekaServer.jar

# Make port 8083 available to the world outside this container
EXPOSE 8083

# Run the jar file 
ENTRYPOINT ["java","-jar","ModEurekaServer.jar"]