# Atributos
Los atributos son valores adicionales que configuran los elementos, tanto para el usuario como para el navegador.

La sintaxis básica de un atributo en una etiqueta HTML sería:
~~~
<etiqueta atributo="valor">
~~~
En el caso en que una etiqueta deba manejar más de un atributo, simplemente estos se van separando por espacios:
~~~
<etiqueta atributo="valor" atributo2="valor2">
~~~
* No existe un límite en verdad en cuanto a la cantidad de atributos que deseamos que maneje la etiqueta, pero tampoco es como que nos encontremos con la necesidad de colocar demasiados.

## Tipos de Atributos:
* **Atributos Básicos**: Se pueden utilizar prácticamente en todas las etiquetas HTML (con algunas pequeñas excepciones).
* **Atributos para Internacionalización**: Los utilizan las páginas que muestran sus contenidos en varios idiomas.
* **Atributos de Eventos**: Sólo se utilizan en las páginas web dinámicas creadas con JavaScript. Sin embargo, estos puede que se encuentren algo obsoletos a día de hoy. Son los que comienzan por _on_ (onClick, onSubmit...).
* **Atribos de Foco**: Están relacionados con la accesibilidad de los sitios web. Que un elemento tenga el foco significa que hemos hecho click sobre él.
* **Atributos Personalizados**: Son atributos que podemos crear nosotros mismos. Deben de comenzar por _data-_. 