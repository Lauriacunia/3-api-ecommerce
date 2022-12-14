# About this project

## Levantar servidor

#### 🔥 Ejecutar el servidor (modos FORK y CLUSTER) con nodemon verificando el número de procesos tomados por node. (en el package json)

```
>npm run start // inicia node
>npm run dev // inicia con nodemon
>npm run cluster // crea cluster, sino por default inicia FORK
```

## Routes

[Ver ENDPOINTS](./docs/routes)

## Documentación Postman

[Ver documentación de la API](https://documenter.getpostman.com/view/13362314/UzBqnjhu)

## ¿Qué dependencias necesito?

[Ver dependencias requeridas](./docs/dependencias)

## Consigna del Trabajo Final

[Ver Consigna](./docs/dependencias)

## 🔥📲 ¿Cómo crear y levantar un proyecto Node Js? 🔥📲

- 1- Crear el package json

```
      npm init
```

- 2- Instalar nodemon de forma global (opcional)

```
       npm install nodemon -g
```

- 3- Crear un scrips en package json para que nodemon se ejecute en cada cambio (opcional)

```
   "scripts": {
         "start": "nodemon server.js"
      },
```

- 4- Para que nodemon se ejecute en cada cambio, ejecutar:
  opcion 1: nodemon server.js
  opcion 2: corriendo el script en package json: npm run start
- 5-Instalar el modulo de express

```
    npm install express
```

- 6- Instalar todas las dependencias que el proyecto requiera.

- 7- Recordá crear el archivo .gitignore para evitar subir contenido innecesario al repositorio.

⏯ [¿Cómo crear gitignore?- Tutorial](https://youtu.be/5tP1Ra73c38)
