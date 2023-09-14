FROM openjdk:17
LABEL maintainer ="eurekaServerMicroService"
ADD target/eurekaservermicroservice-docker.jar eurekaServerMicroService.jar
ENTRYPOINT [ "java","-jar","eurekaServerMicroService.jar" ]