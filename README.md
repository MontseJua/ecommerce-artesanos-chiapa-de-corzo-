# Sistema de E-commerce para Artesanos de Chiapa de Corzo

Proyecto desarrollado con Laravel y Tailwind CSS para la comercialización de artesanías tradicionales de Chiapa de Corzo.

## Tecnologías utilizadas

- Laravel
- PHP
- MySQL
- Tailwind CSS
- Vite
- JavaScript

## Instalación del proyecto

### 1. Clonar repositorio

```bash
git clone https://github.com/MontseJua/ecommerce-artesanos-chiapa-de-corzo-.git
```

### 2. Entrar al proyecto

```bash
cd ecommerce
```

### 3. Instalar dependencias

```bash
composer install
npm install
```

### 4. Configurar entorno

Copiar el archivo `.env.example` y renombrarlo como `.env`

Luego generar la clave:

```bash
php artisan key:generate
```

### 5. Configurar base de datos

Crear una base de datos en MySQL y configurar:

```env
DB_DATABASE=ecommerce_artesanos
DB_USERNAME=root
DB_PASSWORD=
```

### 6. Ejecutar migraciones

```bash
php artisan migrate
```

### 7. Crear enlace de storage

```bash
php artisan storage:link
```

### 8. Ejecutar proyecto

Terminal 1:

```bash
php artisan serve
```

Terminal 2:

```bash
npm run dev
```

## Notas importantes

- El comando `npm run dev` debe permanecer ejecutándose para que Tailwind CSS y Vite carguen correctamente en desarrollo.
- Las imágenes de productos se almacenan mediante Laravel Storage.

