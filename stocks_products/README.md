# Склады и товары

Создание образа, находясь в папке с проектом:

docker build -t crud_try .


Запуск контейнера:

docker run -p 8000:8000 --name crud_try -d crud_try

Теперь, заходя на 
localhost:8000/ 
Есть страничка склада
