﻿# PHP_LARAVEL_SESSION_MANAGER

INDICACIONES

configurar las credenciales para la conexion a la base de datos, para ello buscar el archivo,
".env".

Migrar las tablas para la autentificacion 

Hay que asegurarse de tener definidas las variables de entorno en nuestro archivo .env 
relativas a la base de datos que utilizaremos

comando para la migracion con los seed de que insertan datos:

	php artisan migrate:refresh --seed

o en caso sea primera ves puede intentar

	php artisan migrate 

EN LA RUTA:

	Proyecto->database/seeds/RoleTableSeeders.php

Puede encontrar los roles que se insertan en la tabla roles

	Proyecto->database/seeds/UserTableSeeders.php
    
Para ejecutar el proyecto, ejecute en una consola de comando, relativa al proyecto, la siguiente instruccion:

    php artisan serve
    
Colocar en el navegador web la ruta indicada. Laravel incluye un servidor de prueba junto al asistente artisan que asi mismo integra.

puede observar la insercion de unos usuarios de prueba por defectos con un rol cada uno

Usuario de prueba para credenciales:
User: admin@example.com
Pass: secret

