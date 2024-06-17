FROM openjdk:latest
MAINTAINER sreeramtony@gmail.com
RUN mkdir /consumerservice
ADD hello-consumer-0.0.1-SNAPSHOT.jar /consumerservice
EXPOSE 8081:8081
CMD ["java","-jar","/consumerservice/hello-consumer-0.0.1-SNAPSHOT.jar"]