FROM openjdk:8-jre-alpine
COPY demo-0.0.1-SNAPSHOT.jar /demo-0.0.1-SNAPSHOT.jar
RUN mkdir /keystores
CMD ["java","-Dserver.port=8443","-Dserver.ssl.key-store=file:/keystores/demo.jks","-jar","/demo-0.0.1-SNAPSHOT.jar"]

