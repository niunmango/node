# Ejemplo básico de aplicación de Node.js

Ejecutar como 

`docker run -it --rm -p 3000:8080 --name mi-script -v "$PWD":/usr/src/app -w /usr/src/app node:alpine node app.js`

Para parar el contenedor es neceario ejecutar en otra terminal: `docker stop mi-script`
