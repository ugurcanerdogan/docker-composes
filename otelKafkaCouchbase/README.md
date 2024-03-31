# OpenTelemetry Collector&UIs - Kafka&UI - Couchbase&UI Local Environment

![Couchbase Logo](https://upload.wikimedia.org/wikipedia/commons/6/67/Couchbase%2C_Inc._official_logo.png)
![Kafka Logo](https://logovectordl.com/wp-content/uploads/2021/05/apache-kafka-logo-vector.png)
![Zookeeper Logo](https://upload.wikimedia.org/wikipedia/commons/7/77/Apache_ZooKeeper_logo.svg)
![OpenTelemetry Logo](https://opentelemetry.io/img/logos/opentelemetry-horizontal-color.png)
![Jaeger Logo](https://logowik.com/content/uploads/images/jaeger2618.logowik.com.webp)
![Zipkin Logo](https://zipkin.io/public/img/logo_png/zipkin_vertical_grey_gb.png)
![Prometheus Logo](https://logowik.com/content/uploads/images/prometheus-monitoring-system4911.logowik.com.webp)

This repository uses `docker-compose` to define four services:

- Couchbase at http://0.0.0.0:8091 (username:admin / pwd:password)
- Kafka UI at http://0.0.0.0:8080
- Zookeeper at 0.0.0.0:2181
- Open Telemetry Collector at 0.0.0.0:4317 (OTLP gRPC receiver)
- Jaeger at http://0.0.0.0:16686
- Zipkin at http://0.0.0.0:9411
- Prometheus at http://0.0.0.0:9090

To use it run:

```shell
docker-compose up -d
```

To clean up any docker container run:

```shell
docker-compose down
```
