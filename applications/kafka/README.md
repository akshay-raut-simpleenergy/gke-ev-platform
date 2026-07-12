# Apache Kafka

## Deployment

- Bitnami Helm Chart
- Kafka 4.0.0 (KRaft Mode)
- 3 Brokers
- 3 Partitions
- Replication Factor: 3

## Topic

scooter.telemetry

## Test

Successfully produced and consumed EV telemetry messages using:

- kafka-console-producer.sh
- kafka-console-consumer.sh
