# Kolokwium2
Komendy zad 1
docker pull httpd

docker run --name apache -p 8090:80 -d httpd

docker logs apache

docker stop apache

docker rm apache

docker rmi httpd

