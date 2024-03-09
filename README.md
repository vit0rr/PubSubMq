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


