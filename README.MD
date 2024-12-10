log into the container:
docker compose exec kafka-1 bash
creating topic:
kafka-topics --create --bootstrap-server localhost:19092 --topic kinaction_helloworld --partitions 3 --replication-factor 3
view topic details:
kafka-topics --bootstrap-server localhost:19092 --describe --topic kinaction_helloworld

List topics:
kafka-topics --list --bootstrap-server localhost:19092
