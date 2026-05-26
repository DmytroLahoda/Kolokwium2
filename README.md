
```
Zadanie 1

docker run -d --name apache -p 8090:80
docker ps
http://localhost:8090/
docker logs apache
docker stop apache
docker rm apache
docker rmi httpd

Zadanie 2

docker build .
docker run -d --name app.py -p 8090:80 app
```