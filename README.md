# Marcador-EcuaVoley

Link de la aplicación
```
https://lemito66.github.io/Marcador-EcuaVoley/
```

Intrucciones para el despliegue de github pages

Instrucciones: 

1 Tener lista nuestra aplicación para desplegar. 

    Github Pages solo despliega páginas estáticas. 

2 Crear un nuevo repositorio. 

    Puede ser a través de la consola o en el sitio web. 

3 Instalar gh-pages: npm install gh-pages --save-dev

4 En el archivo package.json agregar las siguientes líneas:

    Con "homepage" indicamos dónde se va a desplegar el sitio. 
    Con predeploy compilamos la aplicación. 
    Con deploy lo desplegamos en github.

```
"homepage": "https://{Github Username}.github.io/{NombreRepo}"
```
```
"predeploy": "npm run build"
```
```
"deploy": "gh-pages -d dist"
```

Ademas de en build añadir la ultima dirección base de la aplicación

```
"build": "vite build --base=/Marcador-EcuaVoley/",
```

link de videos

```
https://www.youtube.com/watch?v=82XNPIiHvOQ&ab_channel=NickPaz
```
```
https://www.youtube.com/watch?v=e3SV6tYztz0&ab_channel=Programaci%C3%B3nenespa%C3%B1ol
```