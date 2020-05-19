# postgres docker master-slave
PostgreSql with built-in replication support is a great choice for a reliable and scalable database engine. The setup that we’re about to discuss consists of 1 master instance which handles both read and write operations and many slave instance which will only serve read requests and that is because writing data is whole different story than reading them.

**this is docker-compose for one pgpool and 7 slave postgres cluster HA**
## download the project

    git clone https://github.com/fcessi/postgres-docker.git
## go to directory

    cd postgres-docker

## for deploy postgres docker

    docker-compose up -d
