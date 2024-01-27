# Docker для Laravel

В **_docker/.env.docker** нужно изменить название проекта.

Запуск контейнера:
```shell
docker-compose --env-file ./_docker/.env.docker  up -d
```

Остановка контейнера:
```shell
docker-compose down
```
