# Using Oracle
This assumes Oracle is running on localhost (or is reachable there, e.g. by means of running it within a VM or Docker container with appropriate port configurations) and set up with the configuration, users and grants described in the Debezium Vagrant set-up.

Also you must download the Oracle instant client for Linux and put it under the directory debezium-with-oracle-jdbc/oracle_instantclient.

# Start the topology as defined in https://debezium.io/docs/tutorial/
export DEBEZIUM_VERSION=1.6
docker-compose up --build

