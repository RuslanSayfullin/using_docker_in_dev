##### _разработка Sayfullin R.R.

Инструкция актуальна для Linux-систем.
========================================================================================================================

$ docker run --rm hello-world  -проверить работоспособность Docker;
$ docker compose version       -проверить работоспособность Docker Compose;
$ sudo systemctl start docker  -запуск демона Docker;

# Создание группы docker-пользователей, включенные в нее, получают разрешение на взаимодействие с Docker Engine
$ sudo groupadd docker
$ sudo usermod -aG docker $USER
$ docker run hello-world

$ docker ps -а  -посмотреть все контейнеры;

Источники:
========================================================================================================================
https://github.com/PacktPublishing/A-Developer-s-Essential-Guide-to-Docker-Compose




curl --location --request POST 'localhost:8080/task/' \
--header 'Content-Type: application/json' \
--data-raw '{
    "id": "8b171ce0-6f7b-4c22-aa6f-8b110c19f83a",
    "name": "A task",
    "description": "A task that need to be executed at the timestamp specified",
    "timestamp": 1645275972000
}'
{"created":true,"message":"Task Created Successfully","tas
k":{"id":"8b171ce0-6f7b-4c22-aa6f-8b110c19f83a","name":"A
task","description":"A task that need to be executed at the
timestamp specified","timestamp":1645275972000}}