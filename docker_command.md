- 👋 Hi, I’m @bsharshenbiev312
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
bsharshenbiev312/bsharshenbiev312 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
~~~
docker run имя_образа - запустить образ<br>
docker ps - отобразить запущенные процессы<br>
docker ps -a - работающие и неработающие процессы<br>
docker stop имя_контейнера - остановить докер<br>
docker rm имя_образа - удалить образ<br>
docker images - отобразить список образов<br>
docker rmi имя_контейнера - удалить контейнеры<br>
docker pull имя_образа - скачать образы<br>
docker exec имя_контейнера - выполнять команду внутри контейнера<br>
docker run -d имя_контейнера sleep 15 - запустить контейнер на 15 секунд<br>
docker rm $(docker ps -aq) - удалить все контейнеры<br>
docker exec имя_контейнера cat /etc/nginx/nginx.conf - зайти в контейнер и просмотреть содержимое файла nginx.conf<br>
docker run --name имя_контейнера -d nginx - запустить контейнер с нужным нам именем<br>
docker rmi ** ** ** ** - удалять образы указывая его отпечаток<br>
~~~

### RUN NAME_IMAGE TAG

~~~
docker run redis - запуск образа
docker run redis:5.0 - устновка конкретной версии образа
docker run -p 5000:80 
docker inspect имя_контейнера - данные о контейнере
