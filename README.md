# dockerStuff
docker stuff for new projects

php:7.4-fpm-alpine<br>
nginx:alpine<br>
mysql:5.7.22<br>
redis:latest<br>

docker ps - покажет запущенные контейнеры.
docker stop 2a, чтобы остановить работу контейнера (2a - первые символы id контейнера)

docker system prune (в случае крайней необходимости - удаляет все контейнеры.
Использовалась когда мы поняли, что одноимённый контейнер уже был создан ранее).

1) docker build -t
После -t идёт имя контейнера всех контейнеров

2) docker-compose up]
стартует контейнеры


