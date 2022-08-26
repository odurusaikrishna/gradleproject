FROM openjdk:8
EXPOSE 8080
ADD build/libs/dockerapp.jar dockerapp.jar
ENTRYPOINT ["java","-jar","/dockerapp.jar"]
