FROM ubuntu:23.10
RUN apt-get update
RUN apt-get install -y default-jre
COPY hello-world-docker-1.0-SNAPSHOT.jar /work/hello-world-docker-1.0-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/work/hello-world-docker-1.0-SNAPSHOT.jar"]
EXPOSE 8080


