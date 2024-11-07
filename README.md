# KafkaDemo Project

This project demonstrates a simple Kafka consumer and producer implementation in Go, using the [Sarama](https://github.com/Shopify/sarama) library.

## Project Structure

- **consumer**: Contains the code for consuming messages from a Kafka topic.
- **producer**: Contains the code for producing messages to a Kafka topic.

## Requirements

- **Go** (version 1.15+ recommended)
- **Apache Kafka** (running on `localhost:9092`)
- **Sarama**: A Go library for Apache Kafka (used for both consumer and producer)

## Setup

1. **Install Go**: Make sure Go is installed on your system. You can download it [here](https://golang.org/dl/).

2. **Install Kafka**: You’ll need a running Kafka server. You can follow the [Apache Kafka Quickstart](https://kafka.apache.org/quickstart) guide to set it up locally.

3. **Install Sarama**: To install the Sarama library, run:
   ```bash
   go get -u github.com/Shopify/sarama
