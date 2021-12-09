FROM adoptopenjdk:11-jre-hotspot

ARG JAR_FILE=*.jar
ARG ENV_FILE=*.env

COPY ${JAR_FILE} application.jar
COPY ${ENV_FILE} .env

ENTRYPOINT ["java", "-jar", "application.jar"]