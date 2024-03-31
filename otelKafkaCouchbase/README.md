# OpenTelemetry Collector Local Environment

![OpenTelemetry Logo](https://opentelemetry.io/img/logos/opentelemetry-horizontal-color.png)

This repository uses `docker-compose` to define four services:

- Open Telemetry Collector at 0.0.0.0:4317 (OTLP gRPC receiver)
- Jaeger at http://0.0.0.0:16686
- Zipkin at http://0.0.0.0:9411
- Prometheus at http://0.0.0.0:9090

By default runs against the `otel/opentelemetry-collector:latest` image. To use it run:

```shell
docker-compose up -d
```

To clean up any docker container run:

```shell
docker-compose down
```