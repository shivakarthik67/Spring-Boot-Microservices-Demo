FROM ubuntu
RUN apt-get update
RUN apt-get install -y openjdk-8-jdk
RUN java -version
RUN apt-get install -y git
RUN apt-get install -y maven
RUN git clone https://github.com/ragasindhun/Spring-Boot-Microservices-Demo.git
WORKDIR /Spring-Boot-Microservices-Demo/MicroserviceDiscoveryServer
RUN ls
RUN mvn clean install
ENTRYPOINT ["java", "-jar", "target/MicroserviceDiscoveryServer-1.0.0.jar"]
