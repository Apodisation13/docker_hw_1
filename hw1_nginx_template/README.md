Создать образ, находясь в папке где лежит этот докерфайл:
docker build -t my_nginx .

После создания он доступен по
docker images

Создать контейнер из этого образа и запустить его:
docker run -p 8080:80 --name my-nginx -d my_nginx

Теперь переходя на localhost:8080/  можно увидеть приветствие из 'custom' html
Остановить контейнер 
docker stop my-nginx
Запустить потом снова
docker start my-nginx
