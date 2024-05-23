Для установки Docker и Docker Compose на Debian выполните следующие шаги:

1. Установите необходимые зависимости:
    $ sudo apt-get update
    $ sudo apt-get install apt-transport-https ca-certificates curl software-properties-common

2. Добавьте официальный ключ GPG Docker:
    $ curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -

3. Добавьте репозиторий Docker в список источников пакетов:
    $ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/debian $(lsb_release -cs) stable"

4. Установите Docker:
    $ sudo apt-get update
    $ sudo apt-get install docker-ce

5. Проверьте версию установленного Docker:
    $ docker --version

6. Установите Docker Compose:
    $ sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    $ sudo chmod +x /usr/local/bin/docker-compose

7. Проверьте версию установленного Docker Compose:
    $ docker-compose --version

Теперь Docker и Docker Compose установлены на вашем Debian. Вы можете начинать использовать их для управления контейнерами и микросервисами.