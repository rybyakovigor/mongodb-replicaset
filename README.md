# MongoDB replicaset

Данный проект позволяет поднять набор replica-set из 3-х контейнеров mongoDB с помощью docker-compose. На машине должен быть установлен docker, docker-compose.

Делаем файлы со скриптами исполняемыми:

```bash
chmod +x rs-init.sh
```

```bash
chmod +x dbstart.sh
```

Запускаем скрипт, который поднимает docker-compose с mongoDB

```bash
./dbstart.sh
```
Строка для подключения к БД:

`mongodb://<host>:27021,<host>:27022,<host>:27023`
