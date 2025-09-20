#start with a base image containing java runtime
FROM openjdk:17-jdk-slim
#information around who maintains the image
MAINTAINER terabytes.com
#add the application jar to the image
COPY target/MyAccountService-0.0.1-SNAPSHOT.jar MyAccountService-0.0.1-SNAPSHOT.jar
#Execute the application
ENTRYPOINT ["java","-jar","MyAccountService-0.0.1-SNAPSHOT.jar"]
