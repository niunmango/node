# Ejemplo básico de aplicación de Node.js

Ejecutar como 

`docker run -dit --rm -p 3000:8080 --name mi-script -v "$PWD":/usr/src/app -w /usr/src/app node:alpine node app.js`

Para parar y borrar el contenedor ejecutar: `docker stop mi-script`
