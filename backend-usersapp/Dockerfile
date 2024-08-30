FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/backend-usersapp-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app_users.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_users.jar"]