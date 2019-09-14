FROM openjdk:latest

# Add Maintainer Info
LABEL maintainer="alagappan.ramasamy@cognizant.com"


ADD target/ModTraining.jar ModTraining.jar

# Make port 8083 available to the world outside this container
EXPOSE 8084

# Run the jar file 
ENTRYPOINT ["java","-jar","ModTraining.jar"]