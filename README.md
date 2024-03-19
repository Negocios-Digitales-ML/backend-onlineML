# Backend Miguel Luna

Este es un proyecto escolar para la materia de Negocios Digitales.

## Clonar el Repositorio

Puedes clonar este repositorio utilizando el siguiente comando en tu terminal:

```bash
git clone https://github.com/Negocios-Digitales-ML/backend-onlineML.git
```

### Configuración de la Base de Datos

Antes de ejecutar el proyecto, asegúrate de crear la base de datos y la tabla necesaria en la base de datos de tu preferencia:

```sql
CREATE DATABASE apliweb;

CREATE TABLE tbl_usuario (
    email VARCHAR(100) PRIMARY KEY,
    password VARCHAR(250) NOT NULL,
    role VARCHAR(20) NOT NULL
);

INSERT INTO tbl_usuario(email, password, role) VALUES ('apliweb@gmail.com', '123456', 'admin');
```

## LOGIN

### URL
```
http://localhost:3000
```

### POST
```json
{
    "email": "apliweb@gmail.com",
    "password": "123456"
}
```

## Peticiones

### URL
```
http://localhost:3000/usuario
```

### POST
```json
{
    "email": "apli@gmail.com",
    "password": "123456",
    "role": "admin"
}
```

### PUT
```json
{
    "email": "apli@gmail.com",
    "password": "admin"
}
```

### DELETE
```json
{
    "email": "apli@gmail.com"
}
```

Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto con el equipo mantenedor del proyecto a través de [correo electrónico](mailto:garraymiguel@gmail.com) 

