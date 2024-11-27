FROM openjdk:23-jdk-slim
ARG JAR_FILE=target/Main-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} Main.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/Main.jar"]