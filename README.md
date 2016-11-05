# Kafka and Zookeeper with Docker

This POC based on [kafka-docker](https://github.com/wurstmeister/kafka-docker).

## Target
 - Run Apache Kafka and Zookeeper with docker/docker-compose

## Requirements
 - Docker version 1.12.3
 - Docker Compose version 1.8.1

## Basic docker up

1. Up docker-compose

	```
	$ docker-compose up -d
	```

2. Scale Kafka
	```
	$ docker-compose scale kafka=3
	```