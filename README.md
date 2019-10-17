# wtfisit

The repository contains the following :

- /Users/eefrat/wtfisit/mysql_repo/mysql/files/docker-entrypoint-initdb.d - contains the init script to bootstrap and seed the mysql db
- [common](#common_repo) - java/maven project with common entity classes
- [producer](#producer_repo) - java/maven project (spring-boot app) that binds to http port 9000 reads from the db and publishes data to kafka
- [consumer](#Consumer_repo) - java/maven project (spring-boot app) that consumes the kafka topic and updates the db
- [kafka](#Kafka_repo) - HA kafka 
- [myqsl](#mysql_repo) - HA mysql deployment 

## to install you can just go to main folder
before using it you should have running k8s with helm 

you need to have helm client 

just helm upgrade -i lola tlc-wtfisit 

i can explain more - please call me if needed 972-50-7943928 
# enjoy 