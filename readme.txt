dentro un container kafka 
/opt/bitnami/kafka/bin/kafka-topics.sh --create --zookeeper zookeeper:2181 --topic mytopic2 --replication-factor 3 --partitions 3