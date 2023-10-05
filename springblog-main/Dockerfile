
# Use a base image suitable for your Java application

FROM openjdk:11

 

# Create a directory to store the agent JAR file

RUN mkdir -p /opt/datadog

 

# Copy the dd-java-agent.jar file into the container

COPY dd-java-agent.jar /opt/datadog/dd-java-agent.jar

 

# Set environment variables if needed

# ENV YOUR_ENV_VARIABLE=value

 

# Define the entry point for your application

CMD ["java", "-jar", "dd-java-agent.jar"]

 