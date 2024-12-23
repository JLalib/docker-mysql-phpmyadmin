# Docker | SQL y PHPMYADMIN

Este contenedor despliega MySQL con una base de datos vacía llamada `genbyte` y credenciales personalizadas, accesible en el puerto `3306`. Incluye PHPMyAdmin para gestionar la base de datos desde una interfaz web en `http://localhost:8080`.

Accede a PHPMyAdmin:

Ve a http://localhost:8080.

Inicia sesión con las credenciales:

Servidor: db

Usuario: genbyte_user

Contraseña: genbyte_password

Vía terminal: docker exec -it mysql_container mysql -ugenbyte_user -pgenbyte_password

SHOW DATABASES;

![image](https://github.com/user-attachments/assets/be9ee10b-9f82-4bbd-b201-dfe6e73c3702)

