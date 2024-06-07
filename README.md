# Gestión de Préstamos

Este es un proyecto de gestión de préstamos a personas y grupos, desarrollado con Laravel 10. La aplicación permite registrar préstamos, pagos, intereses simples y compuestos, así como gestionar usuarios y grupos.

## Requisitos

-   PHP >= 8.1
-   Composer
-   MySQL
-   Node.js y npm (para la compilación de assets)

## Instalación

Sigue estos pasos para instalar y configurar el proyecto en tu entorno local.

1. **Clona el repositorio:**

    ```bash
    git clone https://github.com/tu_usuario/gestion-prestamos.git
    cd gestion-prestamos
    ```

Instala las dependencias de PHP:

bash
Copiar código
composer install
Copia el archivo de entorno y configura tu base de datos:

bash
Copiar código
cp .env.example .env
Edita el archivo .env para configurar tu base de datos:

env
Copiar código
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nombre_de_tu_base_de_datos
DB_USERNAME=tu_usuario
DB_PASSWORD=tu_contraseña
Genera la clave de la aplicación:

bash
Copiar código
php artisan key:generate
Ejecuta las migraciones:

bash
Copiar código
php artisan migrate
Instala las dependencias de Node.js y compila los assets:

bash
Copiar código
npm install
npm run dev
Inicia el servidor de desarrollo:

bash
Copiar código
php artisan serve
Accede a la aplicación en tu navegador en http://localhost:8000.

Características
Gestión de Usuarios: Crear, leer, actualizar y eliminar usuarios.
Gestión de Grupos: Crear, leer, actualizar y eliminar grupos.
Gestión de Préstamos: Registrar préstamos tanto a usuarios individuales como a grupos, especificando monto, tasa de interés y tipo de interés (simple o compuesto).
Gestión de Pagos: Registrar pagos completos o parciales, incluyendo el seguimiento de intereses y recargos.
Contribución
Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

Haz un fork del repositorio.
Crea una rama para tu nueva funcionalidad (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y haz commit (git commit -am 'Agrega nueva funcionalidad').
Empuja tus cambios a la rama (git push origin feature/nueva-funcionalidad).
Crea un Pull Request.
Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

Contacto
Si tienes alguna pregunta o sugerencia, no dudes en abrir un issue o contactarme.
