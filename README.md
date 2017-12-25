## setup command
docker-compose -f cluster.yml up -d

## Stop Command
docker-compose -f cluster.yml down

## recommends 
Apache Cassandra recommends the ‘2 minute rule’. When booting up it must wait 2 minutes between booting up each new node. 