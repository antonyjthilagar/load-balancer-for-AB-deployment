FROM adoptopenjdk/openjdk11:latest
WORKDIR /etc/app/
COPY ./java-webserver.jar .
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "java-webserver.jar"]
