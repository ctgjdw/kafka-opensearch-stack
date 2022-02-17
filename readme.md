# Kafka & OpenSearch stack

Kafka with:
- `Schema Registry`
- `Zookeeper`

OpenSearch with:
- `OpenSearch Dashboard` (Kibana)

## Usage

First create a `Docker` network:
```bash
docker network create "host-net"
```

Kafka:
```bash
docker-compose -f kafka-compose.yml up -d
```

Opensearch:
```bash
docker-compose -f opensearch.yml up -d
```