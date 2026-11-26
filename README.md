# Developing a RESTful API With Node and TypeScript

## Want to learn how to build this project?
build is based on:
Check out the [blog post](http://mherman.org/blog/2016/11/05/developing-a-restful-api-with-node-and-typescript/#.WB3zyeErJE4).

## Want to use this project?
1. Install dependencies - `yarn` | `npm install`
1. Compile assets - `gulp assets`
1. Run the development server -`yarn start | npm start`
1. Test - `npm test`
1. Build Prod to /dest - `yarn run build | npm run build`

## .env variables
generate sample .env file
`npm run setup:env`

After that fill variables located in .env file.

## Developing
1. run `npm start`
2. open `chrome://inspect` in google chrome
[debug to console](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27)
TODO: refresh of console

### Good tool for testing socket.io interface
[gui tool for socket debuging](http://amritb.github.io/socketio-client-tool/)

## REST-API / Socket DOCS
[apiary](https://apiary.io/)

## Production mode
[PM2](http://pm2.keymetrics.io/)

## Ficha del proyecto

Proyecto inicial de microframework para hardware con código Node.js y pruebas.

### Contenido

- [src](./src), [test](./test), [package.json](./package.json).

### Uso

Consulta [package.json](./package.json) para comprobar los requisitos de Node.js y los scripts disponibles en esta revisión.

### Origen

- [Repositorio de origen](https://github.com/mac2394q/boilerplate-hardware-microframework)

<!-- station-x-repository-guide:start -->

## Guía de esta copia

### Mapa del proyecto
[src](./src) contiene la aplicación y [test](./test) sus pruebas. [package.json](./package.json), [tsconfig.json](./tsconfig.json) y [gulpfile.js](./gulpfile.js) describen las herramientas de ejecución y compilación de esta revisión.
### Preparación local
Lee la sección original de variables de entorno y usa valores de prueba. Revisa el comportamiento de `npm run setup:env` antes de preparar tu configuración. El manifiesto ofrece `npm run start`, `npm run build`, `npm run test` y `npm run lint`.
### Verificación
Ejecuta las pruebas del proyecto y, si cambias eventos o rutas, comprueba el contrato REST y Socket.IO desde un cliente local.

<!-- station-x-repository-guide:end -->
