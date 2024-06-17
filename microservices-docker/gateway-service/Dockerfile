FROM openjdk:latest
MAINTAINER sreeramtony@gmail.com
RUN mkdir /gateway
ADD hello-gateway-0.0.1-SNAPSHOT.jar /gateway
EXPOSE 8765:8765
CMD ["java","-jar","/gateway/hello-gateway-0.0.1-SNAPSHOT.jar"]