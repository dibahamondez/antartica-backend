# Antártica Backend

API REST para una librería online, con frontend en React servido desde la carpeta `public`.

## Funcionalidades

- Autenticación de usuarios con JWT y contraseñas cifradas con bcrypt.
- Catálogo de libros y categorías.
- Carrito de compras y pedidos.
- Gestión de usuarios.

## Tecnologías

Node.js · Express · MySQL (mysql2) · JWT · bcryptjs · React (Vite)

## Estructura

```
antartica-backend-main/antartica-backend/
├── public/            # Frontend compilado
└── src/
    ├── config/db.js   # Conexión a MySQL
    ├── middleware/    # Autenticación JWT
    ├── routes/        # auth, books, categories, cart, orders, users
    └── server.js
```

## Cómo ejecutarlo

```bash
cd antartica-backend-main/antartica-backend
npm install
# Crear un archivo .env con los datos de conexión a MySQL y el secreto JWT
npm start
```
