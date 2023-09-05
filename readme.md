# Documentacion de  Practica de Swagger

Este repositorio contiene las documentacion para el ejemplo del la clase correspondiente a la  _comision 51380_

<br>
<br>

## Instalaciones 

ejecutar las siguientes instrucciones

```
 - npm install 
 - npm i swagger-jsdoc
 - npm i swagger-ui-express
```

## Modificar package.json 

```
 "scripts": {
    ...
    "dev": "nodemon -e yaml,js src/app.js",
    ...
  },
```

## Modificar app.js

remplazar  CXN_MONGODB por datos de coneccion 

```
...
const connection = "CXN_MONGODB"
...

```
