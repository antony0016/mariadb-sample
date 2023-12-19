# Maria db with docker compose

## How to run

1. copy .env.example to .env and change the values.

2. create network for mariadb

```bash
docker network create mariadb_network
```

2. run the following command

```bash
docker-compose up -d
```
