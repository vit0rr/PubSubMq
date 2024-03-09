# 
Pub/Sub with RabbitMQ and GoLang

# PubSubMq
Publish/Subscribe - RabbitMQ with GoLang

To run you'll need a RabbitMQ server running.

```bash
➜ docker compose up -d
```

Run worker and newTask

```bash
➜ go run receive-logs/receiveLogs.go
➜ go run main.go
```

https://github.com/vit0rr/PubSubMq/assets/70543018/a59bf885-d1b6-4b0f-835f-85338cbd1c65

