# docker_compose
Some common docker compose files

## ELK stack 

```docker-compose -f elk_stack.yml up -d```

Kibana available at [http://localhost:5601](http://localhost:5601)

Elasticsearch HTTP available at [http://localhost:9200](http://localhost:9200)

## Kafka

```docker-compose -f kafka.yml up -d```

Landoop UI available at [http://localhost:3030](http://localhost:3030)

## Prometheus & Grafana

```docker-compose -f monitoring.yml up -d```

Grafana available at [http://localhost:3000](http://localhost:3000) - to login use `admin/admin`

Prometheus available at [http://localhost:9000](http://localhost:9000)

## Postgres (with PgAdmin)

```docker-compose -f postgres.yml up -d```

PgAdmin available at [http://localhost:5433](http://localhost:5433)

To connect admin to postgres container point it to `host.docker.internal`