FROM openjdk:latest
MAINTAINER sreeramtony@gmail.com
RUN mkdir /producerservice
ADD hello-producer-0.0.1-SNAPSHOT.jar /producerservice
EXPOSE 8082:8082
CMD ["java","-jar","/producerservice/hello-producer-0.0.1-SNAPSHOT.jar"]