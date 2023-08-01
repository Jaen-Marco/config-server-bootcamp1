FROM openjdk:17
VOLUME /tmp
EXPOSE 8888
ADD ./target/spring-config-server-0.0.1-SNAPSHOT.jar scs.jar
ENTRYPOINT ["java", "-jar", "/scs.jar"]