FROM tomcat:9.0.35-jdk14-openjdk-oracle

ENV MONGO_CONNECTOR_JDBC_URL=https://repo1.maven.org/maven2/org/mongodb/mongo-java-driver/3.12.5/mongo-java-driver-3.12.5.jar

RUN curl $MONGO_CONNECTOR_JDBC_URL -o lib/mongodb-connector-java.jar