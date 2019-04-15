# docker_compose
Some common docker compose files

## ELK stack 

```docker-compose -f elk_stack.yml -d```

Kibana available at [http://localhost:5601](http://localhost:5601)

Elasticsearch HTTP available at [http://localhost:9200](http://localhost:9200)

## Kafka

```docker-compose -f kafka.yml -d```

Landoop UI available at [http://localhost:3030](http://localhost:3030)

## Prometheus & Grafana

```docker-compose -f monitoring.yml -d```

Grafana available at [http://localhost:3000](http://localhost:3000) - to login use `admin/admin`

Prometheus available at [http://localhost:9000](http://localhost:9000)

## Postgres (with PgAdmin)

```docker-compose -f postgres.yml -d```

PgAdmin available at [http://localhost:5433](http://localhost:5433)