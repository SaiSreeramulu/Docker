FROM openjdk:latest
MAINTAINER sreeramtony@gmail.com
RUN mkdir /eurekaservice
ADD hello-eureka-service-0.0.1-SNAPSHOT.jar /eurekaservice
EXPOSE 8761:8761
CMD ["java","-jar","/eurekaservice/hello-eureka-service-0.0.1-SNAPSHOT.jar"]