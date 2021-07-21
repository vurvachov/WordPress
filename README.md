# :books: Wordpress en NGINX con PHP-FMP :books:

## :page_with_curl: Para lanzar el docker-compose seguir estos pasos:

:large_blue_diamond: Descargar docker-compose.yml

:large_blue_diamond: Crear fichero .env 

:large_blue_diamond: Rellenar el fichero .env con estos datos:

    En formato MARIADB_VERSION=10.6.3

    ...

Comando | Descripción
------------ | -------------
MARIADB_VERSION | Versión de MariaDB que queremos instalar
ROOT_PASSWORD_DB | Password Root de la BD
DATABASE | Nombre de la base de datos
USER_DB | Usuario para BD
PASSWORD_DB | Password para el usuario BD
WORDPRESS_VERSION | Versión de wordPress que queremos utilizar
WORDPRESS_DB_USER | Usuario de la BD
WORDPRESS_DB_PASSWORD | Password de la BD
NGINX_VERSION | Versión de servidor web que queremos utilizar

:large_blue_diamond: Introducir la sentencia para levantar los servicios declarados en el fichero .yml : 'docker-compose up -d'

    · '-d' sirve para lanzar los servicios del fichero .yml en segundo plano

Listo. :sunglasses: :watermelon:
