# Awesome Pulsar

A curated list of Pulsar tools, integrations, and resources.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Data Processing

- [pulsar-flink](https://github.com/apache/pulsar/tree/master/examples/flink/src/main/java/org/apache/flink/batch/connectors/pulsar/example): A collection of streaming and batch connectors for [Apache Flink](http://flink.apache.org) processing streams in Pulsar. [batch](https://github.com/apache/pulsar/tree/master/examples/flink/src/main/java/org/apache/flink/batch/connectors/pulsar/example) and
  [streaming](https://github.com/apache/pulsar/tree/master/examples/flink/src/main/java/org/apache/flink/streaming/connectors/pulsar/example).
- [pulsar-spark](http://pulsar.apache.org/docs/en/adaptors-spark/): A [Spark Streaming](http://spark.apache.org) receiver to receive data from Pulsar.
- [pulsar-storm](http://pulsar.apache.org/docs/en/adaptors-storm): A Pulsar Spout and Bolt for integrating with [Apache Storm](http://storm.apache.org/) topologies.

## Interactive Query

- [pulsar-presto](http://pulsar.apache.org/docs/en/sql-overview/): A presto connector to query Pulsar topics using SQL

## Kafka

- [Kafka Compatibility wrapper](http://pulsar.apache.org/docs/en/adaptors-kafka/): A Java client wrapper that implement [Apache Kafka](http://kafka.apache.org) Java interface.
- [Kafka Pulsar Connector](http://pulsar.apache.org/docs/en/io-kafka/): Pulsar connectors that receive data from and send data to [Apache Kafka](http://kafka.apache.org)
- [Kafka Connect Adoptor](): A Pulsar Connector that adopts Kafka Connect api and run an existing Kafka connector as a Pulsar connector.

## Logging

- [logstash-input-pulsar](https://github.com/se7enkings/logstash-input-pulsar): A logstash input that receives data from Pulsar.
- [pulsar-beat-output](https://github.com/streamnative/pulsar-beat-output): [Elastic Beats](https://github.com/elastic/beats) to Apache Pulsar.
- [pulsar-flume-ng-sink](https://github.com/streamnative/pulsar-flume-ng-sink): An [Apache Flume](https://github.com/apache/flume) Sink implementation to publish data to Pulsar.
