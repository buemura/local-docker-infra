# Local Docker Infra

Local Docker Infra

## Services:

- Elastic Search
- Elastic APM Server
- Kibana
- PostgreSQL
- MongoDB
- Redis
- Redis Insight (GUI client)
- Zookeeper
- Kafka

## Requirements:

- You need Docker (Required)
- You also need docker-compose (Required)
- node (Optional)

## How to run:

- Using shell script

```bash
sh ./scripts/up.sh
```

- Using npm

```bash
npm run env:up
```

## How to stop:

- Using shell script

```bash
sh ./scripts/down.sh
```

- Using npm

```bash
npm run env:down
```
