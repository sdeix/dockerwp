# 1
## для установки тем нужно добавить define('FS_METHOD', 'direct');
## В файл wp-config.php перед строкой / That's all, stop editing! Happy 
## Также нужно добавить права на папку wp-content.php(пока что 777)


# 2
## Для добавления сертификата на сайт нужно заменить название сервера в server_name в nginx/default.conf
## Запустить контейнер nginx 
## Установить certbot apk add certbot certbot-nginx
## Запустить его certbot --nginx