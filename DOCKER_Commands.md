# Docker command for run Block-scout

## Start the containers

```shell
cd ./docker-compose
```
```shell
docker compose up -d --build
```

## List the started containers

```shell
docker compose up ps -a
```

## View Container's logs

```shell
docker compose logs -f <service_name>
```

```shell
# Example
docker compose logs -f backend
# Or
docker compose logs -f db
# Muliple services
docker compose logs -f backend, frontend,db_init
```

## Destory containers

```shell
docker compose down
```