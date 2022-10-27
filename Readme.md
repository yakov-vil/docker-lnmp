Docker-compose для разворачивания LNPM (NGINX + php-fpm + mariadb).
Пример с nginx-конфигурациями:
1. Yii2
2. DLE
3. Bitrix

**Установка**

1. cd /path/to/project/
2. git clone https://github.com/yakov-vil/docker-lnmp.git docker
3. cd docker
4. docker-compose -p ${NAME_CONTAINER} up 
где ${NAME_CONTAINER} название проекта. Если не указывать, тогда будет по категории в которой находится

Примечание:
1. Если необходимо развернуть базу при создании проекта, тогда в самом проекте должна быть директория sql c дампом БД
2. Переменные окружения находятся в файле .env 