FROM adoptopenjdk/openjdk11
VOLUME /tmp
ADD spring-cloud-config-server-0.0.1-SNAPSHOT.jar config-server.jar
EXPOSE 9006
ENTRYPOINT ["java","-jar","/config-server.jar"]
