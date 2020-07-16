# Tipos de Etiquetas HTML
---
## Metadatos
Existen varios elementos meta:
* **head**: Representa una colección de metadatos para el documento.
* **title**: Título de la página.
* **base**: Establece un link/atributo global para los enlaces.
* **link rel="relaciónArchivo" href="ruta"**: Trae un archivo externo a nuestro documento.
* __style__: Escribe código CSS dentro del documento HTML.
* __script__: Escribe código JS dentro del documento.
---
## Sección
Las etiquetas de sección sirven para añadir bloques de contenido.

Existen 8 etiquetas de sección:
* **body**: Todo el contenido de nuestra página.
* **article**: Representa un contenido completo dentro de otra sección. Se recomienda que dentro de este exista un encabezado.
* **h1-h6**: Es un título de sección o bloque. También indica la importancia de ese bloque.
* **section**: Divide un bloque de contenido.
* **aside**: Representa un contenido relacionado con el contenido principal.
* **header**: Representa la cabecera de un bloque de contenido.
* **footer**: Representa el pie de un bloque de contenido.
* **nav**: Representa los enlaces de navegación de la página.
---
## Agrupación
---
## Semánticas a nivel de Texto
Estas etiquetas son solamente elementos de línea.
* **a**: La etiqueta a representa un link. Representa la base de una web.
* **em**: La etiqueta em representa el énfasis del contenido. Aunque se muestre en cursiva, su intención no es dar estilo. es para indicar al navegador que X palabra tiene relevancia en el contexto de ese párrafo.
* **strong**: Representa un elemento de gran importancia. Es el siguiente nivel a 'em'. El navegador lo representa con negrita, pero no se utiliza para dar estilo de negrita al texto.
* **small**: Representa contenidos secundarios, como la letra pequeña. No es relevante para el contenido de la página, pero necesitamos mostrar.
* **cite**: Representa una referencia a un trabajo. Se utiliza para cuando necesitamos citar frases o contenido de otro trabajo.
* **q**: Representa un contenido de frase citado de otra fuente. A diferencia de la etiqueta cite, en _q_ estamos trabajando contenido en una sola línea.
* **code**: Se utiliza para representar fragmentos de código.
* **sub**: Se utiliza para representar un subíndice.
* **sup**: Representa un superíndice. Algo similar a la representación de una exponenciación.
* **span**: Es similar a _div_. Es útil cuando se utiliza junto a atributos globales como _class_. Se utiliza sobre todo para elementos CSS.
* **br**: Fuerza al navegador a realizar un salto de línea.
* **wbr**: Representa un salto de línea opcional.

---
## Contenido Embedido
El contenido embebido es aquel que nos traemos desde fuera para mostrarlo en nuestra página web.
Para ello, contamos con algunas etiquetas como:
* **img src="ruta_archivo" alt="descripción"**: Traemos imágenes desde una página o desde una carpeta.
* **audio src="ruta_archivo"**: Podemos traer un fichero de audio desde un directorio local o desde una url.
* **video src="ruta_archivo"**: Trae un archivo de video desde un directorio local o desde un enlace.
* **iframe src="url**: Un _iframe_ es una sección de posible contenido multimedia, por lo que puede alvergar contenido de un video o mapas, por ejemplo.

---
## Enlaces
En contexto de HTML, existen dos tipos de rutas:
* **Absolutas**: Son únicas y siempre conducen al mismo sitio. Por ejemplo: https://www.google.com
* **Relativas**: Están en relación a la ubicación del archivo. Se pueden subidividir en dos tipos:
  * A la carpeta actual
  * A la raíz del servidor

Generalmente, en tema de enlaces, la diagonal ( _/_ ) representa a la raíz del servidor. 
* Para subir un nivel, utilizamos los dos puntos: _../_

Según cómo se trabaje, los enlaces en las etiquetas HTML pueden ser vistos principalmente como atributos o como una etiqueta, siendo tal:
* **link**: Etiqueta utilizada para enlazar contenido hacia nuestro documento HTML. Definimos la fuente a través del atributo _href_.
* Atributo **src**: Utilizado para decirle al documento desde dónde queremos obtener cierta fuente de contenido para desplegar en nuestra aplicación.