# CRUD ANGULAR - SPRING BOOT

<p> Este proyecto explora la creación de un CRUD hecho con Angular 17, Spring Boot 3, Spring Data Rest para agilizar nuestro CRUD y como Base de Datos se uso Mysql.
Usaremos en nuestra app de Spring HATEOAS que proporciona métodos y clases para incluir los enlaces de hypermedia de las entidades que se devuelven como resultado en el servicio.</p>

## Instalación

###Paso 1:
- Clonar el Repositorio:

```
git clone https://github.com/WalterDanielMachacaChoque/Crud_Frontend-Backend

```

### Paso2:

- Crear una base de datos con el nombre "**db_backend_products**" esta de preferencia Mysql, aunque si se desea usar otra lo debe cambiar en el **application.properties**, a continuación se muestra el script para ejecutar:

```
-- Step 1: Create the database
CREATE DATABASE db_backend_products;

-- Step 2: Select the database to work with
USE db_backend_products;

-- Step 3: Create the table with the required columns
CREATE TABLE products (
    id INT AUTO_INCREMENT PRIMARY KEY,  -- Primary key, not null, auto-incremented
    name VARCHAR(100),                   -- Name of the product
    description TEXT,                    -- Description of the product
    price DECIMAL(10, 2)                 -- Price with two decimal points
);
```

## Vista Previa.

### Listado de Productos.

![My Image](https://i.postimg.cc/wxS7p904/Lista-de-productos.jpg)

### Agregando un producto nuevo:

![My Image](https://i.postimg.cc/Lsbm3VWQ/Agregando-Productos.jpg)

### Actualizando un Producto:

![My Image](https://i.postimg.cc/9XTcyZY1/Actualizar.jpg)

### Eliminando Productos:

![My Image](https://i.postimg.cc/Vvj11Pk2/Eliminar.jpg)

## Recomendaciones:

<p>El puerto elegido para el Backend es el "8083", usted puede elegir el que mas le guste.</p>
