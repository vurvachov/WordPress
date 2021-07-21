#DOCKER-COMPOSE WORDPRESS CON NGINX Y PHP-FMP

Para poner lanzar el docker-compose seguir estos pasos:

-> Descargar docker-compose.yml

-> Crear fichero .env 

-> Rellenar el fichero con los datos:

    MARIADB_VERSION=Versión de MariaDB que queremos instalar
    ROOT_PASSWORD_DB=Password de Root de la base de datos
    DATABASE=Nombre de la base de datos
    USER_DB=Usuario para BD
    PASSWORD_DB=Password para el usuario BD
    WORDPRESS_VERSION=Versión de wordPress que queremos utilizar
    WORDPRESS_DB_USER=Usuario de la BD
    WORDPRESS_DB_PASSWORD=Password de la BD
    NGINX_VERSION=Versión de servidor web que queremos utilizar

-> Para lanzar docker-compose tenemos que poner esta sintencia: 'docker-compose up -d'
