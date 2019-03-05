Testing Large Messages with AMQ 7 Broker
=========================================

Testing how to stream large messages with AMQ 7 broker with Fuse 6.3.

To build this project use

    mvn install

To run the project you can execute the following Maven goal

	export MAVEN_OPTS="-Xmx128m"
    mvn camel:run

To deploy the project in OSGi. For example using Apache Karaf.
You can run the following command from its shell:

    osgi:install -s mvn:com.mycompany/camel-blueprint/1.0.0-SNAPSHOT

For more help see the Apache Camel documentation

    http://camel.apache.org/
