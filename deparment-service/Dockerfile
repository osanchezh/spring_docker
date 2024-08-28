FROM openjdk:17

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} department-ser.jar

ENTRYPOINT ["java", "-jar", "/department-ser.jar"]

EXPOSE 8081