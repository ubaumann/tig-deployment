# Docker Compose for demo TIG stack

## Services

- Telegraf
- InfluxDB
- Grafana

## Deploy

```bash
docker-compose up -d
```

Will deploy Telegraf, InfluxDB and Grafana. To configure initial username, password, bucket name or token, change .env.
Telegraf will listen for telemetry data from cisco devices on port 57400 by default. Edit services/telegraf/etc telegraf/telegraf.conf to adjust.
