FROM openjdk:17

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} servicereg.jar

ENTRYPOINT ["java", "-jar", "/servicereg.jar"]

EXPOSE 8761