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
https://github.com/PacktPublishing/Full-stack-Django-and-React


