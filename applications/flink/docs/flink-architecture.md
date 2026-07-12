# Apache Flink Architecture

## Source
Apache Kafka

## Processing

- Parse JSON
- Filter invalid events
- Detect overspeed
- Detect battery low
- Calculate aggregates

## Sink

Apache Pinot

## Cluster

- JobManager: 1
- TaskManagers: 2

## Data Flow

Kafka → Flink → Pinot
