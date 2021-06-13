FROM openjdk:11-jre-slim
COPY target/docker-learn-0.0.1-SNAPSHOT.jar /opt/
WORKDIR /opt/
ENTRYPOINT java -jar docker-learn-0.0.1-SNAPSHOT.jar
EXPOSE 8080