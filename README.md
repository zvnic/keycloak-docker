# keycloak-docker
<p>
Keycloak docker container
</p>

Создайте на основе .env.dist файл .env и отредактируйте в нем переменные окружения
> cp .env.dist .env


Создайте самоподписанный SSL-сертификат
> penssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout server.key -out server.crt

