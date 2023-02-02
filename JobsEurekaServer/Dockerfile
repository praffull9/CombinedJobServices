FROM openjdk:17
LABEL maintainer="praffull@sohamglobal.com"
ADD target/AutomobileEurekaServer-0.0.1-SNAPSHOT.jar AutoEurekaServer.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","AutoEurekaServer.jar"]