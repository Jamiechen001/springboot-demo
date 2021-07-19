FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY /buildTest/target/demo-0.0.1-SNAPSHOT.jar /var/app.jar
ENTRYPOINT ["java","-jar","/var/app.jar"]