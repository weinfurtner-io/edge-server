FROM java:8
MAINTAINER jared@weinfurtner.io
ADD edge-server-0.0.1-SNAPSHOT.jar edge-server.jar
RUN sh -c 'touch /edge-server.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/edge-server.jar"]