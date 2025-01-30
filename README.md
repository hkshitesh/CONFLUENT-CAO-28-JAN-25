## Pull command for Ex 1C

docker pull cnfltraining/test-consumer-net:2.0

docker pull cnfltraining/test-producer-net:2.0

## Extra Commands for Lab Ex 10
Base Broker Image Name

confluentinc/cp-enterprise-kafka:latest-ubi8

yum install -y iptables

## Lab 10 B command
docker-compose exec -u root kafka-1 yum install -y iptables && docker-compose exec -u root kafka-2 yum install -y iptables && docker-compose exec -u root kafka-3 yum install -y iptables
