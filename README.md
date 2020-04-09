# Simple REST API with Nodejs and Mongodb

En este repositorio se almacena el código escrito en [tutorial para crear una REST API usando Nodejs, Mongodb](https://www.youtube.com/watch?v=OtYoK0RV7oY&list=PLtGPr3LoS9SbftwyFA84MMoUBq5wCJORt&index=2&t=145s) y sintaxis moderna de Javascript usando Ecmascript 10 o Ecmascript 2019.

Para transpilar código de Javascript se hace uso de Babeljs.


## Comandos Utilizados configuración entorno de Trabajo

A continuación los comandos utilzados para la creación del proyecto

    >  use el flag `--save` para incluir estos en el package.json.
    >  use el flag `--save-dev` ó `-D` para incluir los packetes pero como dependencias de desarrollo.

Iniciar el package .json de npm

```
    npm init -y
```

Instalación Express y MongoDB ()

```
    npm install express mongodb --save
```

Intalación de Babel 

```
    npm install --save-dev @babel/core @babel/cli @babel/preset-env
    npm install --save @babel/polyfill
```

Instalación Babel-Node para usar el transpilador de babel del lado del servidor

```
    npm install --save-dev @babel/core @babel/node
```



## Paquetes que deben estar preinstalados 

[Instalación MongoDB](https://www.digitalocean.com/community/tutorials/como-instalar-mongodb-en-ubuntu-18-04-es)