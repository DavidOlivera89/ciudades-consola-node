# Aplicación de consola interactiva Ciudades

Aplicación de consola desarrollada en Nodejs, que obtiene información de una ciudad, utilizando la api de Mapbox.

## Requeriments

* Es necesario tener instalado Nodejs
* Es necesario tener una cuenta en Mapbox.com para obtener el token de acceso a los servicios de la api

## Installation

1- clonar el repositorio:

```
git clone "https://github.com/DavidOlivera89/ciudades-consola-node.git"
```

2-En el directorio raíz ejecutar el comando:

```
npm i
```

3-Crear una cuenta en mapbox.com, crear un token de acceso a la api.

4-En el archivo .env crear la variable de entorno borrando la palabra token y pegando allí su token correspondiente:

```
MAPBOX_KEY=token
```

5-En el directorio raiz ejecutar el comando

```
node index.js
```
