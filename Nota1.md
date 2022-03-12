# CSS

* Cascading Style Sheets

* Hoja de estilo de cascada

> Lenguaje basado en reglas

Las reglas determinarán el estilo  que se aplicará a un elemento o a un grupo de elementos.

# ¿Cómo escribir ese conjunto de reglas?

1. Estilos de línea
    * El estilo se añade directamente a la etiqueta de apertura del elemento HTML.
    * Ejemplo
        <h2 style = "color: purple" >Ximena</h2>
    + Especificamos que le color de este texto sea purpura.
        * Incluimos la información como un atributo en la etiqueta de

2. Usar bloque style
    * Añadimos el elemento style en head para describir el estilo.
    * Ejemplo
    En este caso h2 es un selector (ver el código original)
    <head>
        <style>
         h2 { 
             color: blue;
         }
        </style>
    </head>

3. Archivo .css

> Creamos un archivo de tipo .css para definir el estilo de la página.

* Vamos a vincular los siguientes archivos.

.html + .css

* Esta es la mejor opción.
