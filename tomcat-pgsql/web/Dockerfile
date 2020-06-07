FROM tomcat:9.0.35-jdk14-openjdk-oracle

ENV PGSQL_CONNECTOR_JDBC_URL=https://repo1.maven.org/maven2/org/postgresql/postgresql/42.2.13/postgresql-42.2.13.jar

RUN curl $PGSQL_CONNECTOR_JDBC_URL -o lib/postgresql-connector-java.jar