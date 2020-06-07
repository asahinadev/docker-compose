FROM tomcat:9.0.35-jdk14-openjdk-oracle

ENV MYSQL_CONNECTOR_JDBC_URL=https://repo1.maven.org/maven2/mysql/mysql-connector-java/8.0.20/mysql-connector-java-8.0.20.jar

RUN curl $MYSQL_CONNECTOR_JDBC_URL -o lib/mysql-connector-java.jar