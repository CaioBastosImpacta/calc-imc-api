FROM openjdk:11-jdk-slim
VOLUME /tmp
ADD app/target/imc-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8081
ENTRYPOINT [ "java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/app.jar" ]
