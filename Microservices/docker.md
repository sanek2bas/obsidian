Досмотреть последнюю часть по докеру
https://www.youtube.com/watch?v=ZbOmhm8Q2_I&list=PLA0M1Bcd0w8zznkO6nZoG8pWfKGK0RqBo&index=11



docker run -d --rm --name psgr --network dbnet -e POSTGRES_DB=mydata -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=1234 postgres:17-alpine

-d - фоновый режим
--rm удалять контейнер при остановке
--network dbnet используется виртуальная сеть dbnet
-e - переменная окружения (указывается название и ее значение)


docker exec -it psgr psql -U postgres
обращение к контейнеру psgr в интерактивном режиме + создается отдельным процессом psql под пользователем postgres
(стандартная утилита командной строки, которая выступает в роли терминального клиента для взаимодействия с базами данных PostgreSQL)

docker run --rm -d --network dbnet --link psgr:db -p 8080:8080 adminer
создание контейнера adminer для подключения к контейнеру psgr
--link psgr:db связывает контейнер psgr с псевдонимом db


docker run -d --rm --name psgr --network dbnet -e POSTGRES_DB=mydata -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=1234 -v postgres-data:/var/lib/postgresql/data postgres:17-alpine

-v postgres-data:/var/lib/postgresql/data
	добавляется новый том с именем и расположением, чтобы при удалении контейнера данные не терялись