#use base image with java 17
FROM openjdk:17-jdk-slim

# set working directory
WORKDIR /app

# copy the jar file to the container
COPY . .

# compile
RUN javac Main.java

# run the application
CMD ["java", "Main"]
