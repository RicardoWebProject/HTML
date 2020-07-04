# Sintaxis de HTML
* La sintaxis de HTML consiste en el contenido de una etiqueta, encerrado entre la etiqueta de apertura y la etiqueta de cierre.
* Una etiqueta de apertura se compone del símbolo _menor qué_ (<), _el nombre de la etiqueta_, de forma opcional se le pueden añadir **atributos**; y cerrando la apertura con el símbolo _mayor qué_ (>), procedemos a construir el contenido de esa etiqueta.
* Para cerrar la etiqueta, se escribe exactamente igual que la apertura, pero _colocando al principio el slash (o barra invertida)_.
* Por ejemplo:
    ~~~
    <h1 id="title">Soy un encabezado principal</h1>
    ~~~
* Los atributos son opcionales, salvo en algunas etiquetas donde son obligatorios.
* Existen etiquetas **_self-closing_** o etiquetas vacías (que no se cierran).
* Por ejemplo:
    ~~~
    <img src="foto.jpg">
    ~~~
----------
## Estructura Básica de un documento de HTML
* Actualmente, en HTML5, para especificar un documento HTML, se debe escribir:
    ~~~
    <!DOCTYPE html>
    ~~~
* Esta anterior sería la etiqueta que le dice al navegador qué tipo de archivo leerá.
* Después de esto, escribiríamos la etiqueta **<html>**, que es la que da comienzo a todo un documento html:
    ~~~
    <html lang="es">
    ...
    </html>
    ~~~
* Después de ello, tendríamos la etiqueta **<head>**. Dentro de esta tenemos algunas etiquetas meta y el título del documento que leerá el navegador. Aquí escribimos, básicamente, la información a proporcionarle al navegador:
    ~~~
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    ~~~
* Después de esta etiqueta, tendríamos la etiqueta **<body>**. Aquí encerramos todo el contenido que tendrá la página, y que sí se verá a través del navegador:
    ~~~
    <body>
    ...
    </body>
    ~~~
* Opcionalmente, se puede agregar, después de esta última etiqueta, una etiqueta llamada **<footer>**, donde se pueden colocar algunos elementos de JS, actuando también como un "pie de página" para el documento:
    ~~~
    <footer>
    ...
    </footer>
    ~~~
* Con esta estructura general, tendríamos un esquema básico de un documento HTML donde, claramente, puede crecer dependiendo del contenido que se desarrolle según sea necesario:
    ~~~
    <!DOCTYPE html>
    <html lang="es">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
        </head>
        <body>
            ...
        </body>
        <footer>
            ...
        </footer>
    </html>
    ~~~