FROM openjdk:17
LABEL maintainer="praffull@sohamglobal.com"
ADD target/ApiGateway-0.0.1-SNAPSHOT.jar AutoAPIGateway.jar
EXPOSE 8083
ENTRYPOINT ["java","-jar","AutoAPIGateway.jar"]