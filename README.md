# Kolokwium2
Komendy zad 1
docker pull httpd

docker run --name apache -p 8090:80 -d httpd

docker logs apache

docker stop apache

docker rm apache

docker rmi httpd

Komendy zad 2

docker build -t app .

docker run --name application -p 5000:5000 -d app

Komendy zad 3

docker compose up -d