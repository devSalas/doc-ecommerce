# Rutas Usuarios

## Registrar  un usuario.

```js title="POST"
  https://ecomerce-backend-wo0w.onrender.com/register
```
Datos que deben ser enviados para registrar al usuario.   

     


```js title="BODY"
  {
    name:"esteban",
    email:"esalassulca@gmail.com",
    password:34343434
  }
```




## Realizar un inicio de sesion.

```js title="POST"
  https://ecomerce-backend-wo0w.onrender.com/login
```
```js title="BODY"
  {
    email:"esalassulca@gmail.com",
    password:343434343
  }
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