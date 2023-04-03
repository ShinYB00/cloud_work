FROM openjdk:11

#간단하게 사용할 수 있도록 수정
COPY target/spring-docker-*.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]