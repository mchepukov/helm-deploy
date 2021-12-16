kafka-topics.sh --zookeeper 10.235.88.22:2181 --create --topic devices-data --partitions 12 --replication-factor 1
kafka-topics.sh --zookeeper 10.235.88.22:2181 --create --topic devices-payload --partitions 12 --replication-factor 1


kafka-topics --zookeeper 10.235.88.22:2181 --topic devices-payload --describe