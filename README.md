Esta es una plantilla de ejemplo para usar en APIs personales o de ámbito empresarial, hecho completamente en Laravel y usando la librería Laravel Rest API de Lomkit

## Prerrequisitos de instalación

• PHP 8.1+
• Laravel 10.0+
• Composer

## Librerías usadas

• lomkit/laravel-rest-api v2.8

## Pasos a seguir

1. Instalar dependencias con `composer install`
2. Sacar una copia de `.env.example` y renombrarlo como `.env` y editar la conexión de base de datos.
3. Generar clave de encriptación `php artisan key:generate`
4. Correr las migraciones generadas por defecto (se pueden modificar a conveniencia) `php artisan migrate`
5. Cambiar en el archivo `.env` la configuración de la variable `SESSION_DRIVER` a `file`.
6. Levantar el servidor de artisan con `php artisan serve`
