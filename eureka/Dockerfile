FROM openjdk:8
EXPOSE 8761
ADD target/docker-eureka.jar docker-eureka.jar
ENTRYPOINT ["java","-jar","/docker-eureka.jar"]