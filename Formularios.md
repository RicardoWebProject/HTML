# Formularios
Los formularios son uno de los puntos principales para la interacción del usuario con la página web. Con los formularios, se puede introducir información desde la página para poder ser procesada por un servidor.

Para enviar un formulario tenemos _dos opciones_:
* **Backend**: Haciendo que la información se envíe directamente al servidor. Por ejemplo, un servidor con PHP.
* **Frontend**: Haciendo que el propio navegador interactúe con el servidor usando JavaScript.

## Etiquetas:
Existen seis etiquetas principales para los formularios:
* **form**: Es la etiqueta que construye el formulario, y todas las demás etiquetas deben estar dentro de este.
* **label**: El nombre del campo.
* **input**: Son los campos del formulario donde se ingresarían los datos.
* **select**: Representa un control que muestra un menú de opciones. Es la etiqueta padre a las etiquetas _option_.
* **text**: Por default, define una entrada de texto.
* **button**: Actúa de la misma manera que submit. (Envía el formulario)

Además de las etiquetas anteriores, también se emplean en formularios las siguientes etiquetas, de acuerdo a las necesidades que se tengan:
* **textarea**: Es una etiqueta que designa un espacio donde se podrá escribir una buena cantidad de texto en un formulario.
* **datalist**: Permite autocompletar cajas de texto creadas con la etiqueta input. Despliega un listado de posibles selecciones.
* **password**: Es un campo para contraseñas. Sin embargo, no encripta nada, solamente oculta.
* **number**: Permite introducir únicamente valores numéricos.
* **submit**: Botón para enviar un formulario.
* **image**: Envía el formulario usando una imagen personalizada
* **reset**: Reinicia el formulario vaciando los campos.