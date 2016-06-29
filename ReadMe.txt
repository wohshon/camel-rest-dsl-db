Camel ActiveMQ Project
======================

This project embeds Apache ActiveMQ together with Apache Camel.

To build this project use

    mvn install

To run this project use the following Maven goal

    mvn camel:run

For more help see the Apache Camel documentation

    http://camel.apache.org/

    mvn clean install
in fuse, 
features:install activemq
install -s wrap:mvn:org.apache.commons/commons-dbcp2/2.1.1
install -s wrap:mvn:org.apache.commons/commons-pool2/2.4.2
install -s wrap:mvn:org.mariadb.jdbc/mariadb-java-client/1.4.6
install -s mvn:com.demo/fuse-demo/1.0

requires a mariadb db at localhost:3306 with 'demotable' and id , value coloumns
