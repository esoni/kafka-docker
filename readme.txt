dentro un container kafka 
/opt/bitnami/kafka/bin/kafka-topics.sh --create --zookeeper zookeeper:2181 --topic mytopic2 --replication-factor 3 --partitions 3


/opt/bitnami/kafka/bin/kafka-topics.sh --create --zookeeper zookeeper:2181 --topic mytopic2 --replication-factor 1 --partitions 3


https://medium.com/jinternals/kafka-ssl-setup-with-self-signed-certificate-part-1-c2679a57e16c
ssl 
openssl req -new -newkey rsa:4096 -days 365 -x509 -subj “/CN=Demo-Kafka” -keyout ca-key -out ca-cert -nodes
https://docs.confluent.io/current/kafka/authentication_ssl.html
https://github.com/dilipsundarraj1/kafka-for-developers-using-spring-boot/blob/master/Kafka_Security.md