# Rutas Productos

## Obtener los datos de todos los productos.

```js title="GET"
  https://ecomerce-backend-wo0w.onrender.com/api/product
```
## Obtener un producto por ID.

```js title="GET"
  https://ecomerce-backend-wo0w.onrender.com/api/product/:id
```
## Crear un producto.

 Ingresa un producto a la base de datos con esta url.

```js title="POST"
  https://ecomerce-backend-wo0w.onrender.com/api/product/:id
```
Datos que deben ser enviados para crear el producto.

```js title="Body"
    {
    "title":"main board",
    "price":320,
    "description":"Marca Asus",
    "category":"tecnology",
    "image_url":"https:/mainboardAsus.jpg",
    "stock":5
    }
```