


# 🚀 GuitarLA Strapi API 

Esta API proporciona datos sobre guitarras, incluyendo su nombre, precio, características, etc. También incluye un blog relacionado con guitarras para el sitio web de un eCommerce de venta de guitarras.
Esta API fue realizada para un E-commerce de venta de guitarras GUITAR-LA se alimente de estos datos, dichos proyectos los puedes encontrar en mi github, hay uno realizado en Remix, otro en NextJS y otro en Astro; todos ellos como parte de mi preparación en un curso de React. 

## Requisitos previos
Node.js (versión 18.17.0)
PostgreSQL (versión 14) configurado con las credenciales adecuadas.

## Instalación
```

Clona este repositorio en tu máquina local.
Ejecuta npm install para instalar las dependencias necesarias.
Configura las variables de entorno necesarias para la conexión a la base de datos PostgreSQL.

```
## Uso
### Iniciar el servidor
  

```npm start
 
```
## Consulta de Datos de Guitarras
 

```# Obtener todas las guitarras
GET https://guitarla-strapi-vm6q.onrender.com/guitarras

# Obtener una guitarra por ID
GET https://guitarla-strapi-vm6q.onrender.com/guitarras/:id
 
```

## Consulta del Blog de Guitarras
 
  
```# Obtener todos los artículos del blog
GET https://guitarla-strapi-vm6q.onrender.com/blog

# Obtener un artículo del blog por ID
GET https://guitarla-strapi-vm6q.onrender.com/blog/:id
 
```
## Documentación API
Puedes encontrar la documentación completa de la API aquí.

## Contribución
¡Gracias por considerar contribuir a Guitarla Strapi! Si deseas enviar alguna mejora o corrección, por favor sigue estos pasos:

Crea un fork del repositorio.
Crea una nueva rama con el nombre de la función o corrección: git checkout -b feature/nueva-funcion o git checkout -b fix/correccion.
Realiza los cambios necesarios y commitea los cambios: git commit -m 'Añadir nueva función'.
Envía los cambios a tu fork: git push origin feature/nueva-funcion.
Abre un Pull Request en el repositorio original.

Reportar problemas
Si encuentras algún problema o tienes alguna sugerencia, por favor crea un ***issue*** en el repositorio.

Licencia
Este proyecto está bajo la Licencia MIT.

Contacto
Si tienes alguna pregunta o comentario, no dudes en ponerte en contacto con nosotros en contact@guitarla.com.