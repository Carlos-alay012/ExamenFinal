FROM openjdk:17
VOLUME /tmp
ENV IMG_PATH=/img
EXPOSE 8080
RUN mkdir -p /img
ARG JAR=target/*.jar
COPY ${JAR} app.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]