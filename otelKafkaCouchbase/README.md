# OpenTelemetry Collector & Jaeger UI - Kafka&UI - Couchbase&UI Local Environment

This repository uses `docker-compose` to define four services:

- Couchbase at http://0.0.0.0:8091 (username:admin / pwd:password)
- Kafka UI at http://0.0.0.0:8080
- Zookeeper at 0.0.0.0:2181
- Open Telemetry Collector at 0.0.0.0:4317 (OTLP gRPC receiver)
- Jaeger at http://0.0.0.0:16686

To use it run:

```shell
docker-compose up -d
```

To clean up any docker container run:

```shell
docker-compose down
```

<img src="https://upload.wikimedia.org/wikipedia/commons/6/67/Couchbase%2C_Inc._official_logo.png" width="200">
<img src="https://logovectordl.com/wp-content/uploads/2021/05/apache-kafka-logo-vector.png" width="200">
<img src="https://upload.wikimedia.org/wikipedia/commons/7/77/Apache_ZooKeeper_logo.svg" width="200">
<img src="https://opentelemetry.io/img/logos/opentelemetry-horizontal-color.png" width="200">
<img src="https://logowik.com/content/uploads/images/jaeger2618.logowik.com.webp" width="200">

