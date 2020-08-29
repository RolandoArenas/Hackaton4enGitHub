Para que sirve CSS?
    Hojas de Estilos de Cascada o CSS por sus siglas en inglés, es el lenguaje que sirve para darle estilos a una presentación en HTML. Mientras que los comandos HTML le indican al navegador que ciertas partes del texto son títulos, subtítulos, párrafos, enlaces, etc., CSS le indica qué alineación deben tener los distintos elementos de la presentación (maquetación) así como su fuente, tamaño, color, fondo, etc... 
    Para darle estilos a una presentación en HTML, por convención se crea una carpeta llamada “css o styles” en la raíz. Ya en ella, se crea un archivo principal normalmente llamado “style.css” así como otros archivos con reglas de estilo esenciales ("reset.css" o "fonts.css"). Estos archivos se enlazan con el documento HTML de 3 formas:
        - Se enlaza el archivo CSS al archivo HTML mediante la siguiente regla en el head del HTML: <link rel="stylesheet" href="(URL del archivo .css)">
        - También se puede ingresar las reglas CSS en el mismo archivo HTML mediante las etiquetas <style></style>. Se recomienda hacer esto solamente en el caso de documentos muy pequeños.
        - Por último, se puede poner un atributo inline style="#" dentro de la etiqueta. Por ejemplo: <h1 style="color: blue;">Hola mundo</h1> afichará el "Hola mundo" en azul. 
    

Cuales son los contras de no usar CSS?
    Al no usar CSS un archivo HTML se aficharía solamente con textos y unos estilos muy básicos. No existiría la "personalización" de la página web. 
    

Cuales son los beneficios?
    Cuando enlazamos un archivo HTML a una hoja de estilos CSS, esta tiene una serie de comandos que modifican a todos los elementos que concuerden con determinado criterio. Así, personalizamos la presentación determinando la alineación de los diversos elementos (maquetación) y su fuente, tamaño, color, fondo, etc...
    Otra de las ventajas de tener una hoja de estilos CSS es que esta puede ser utilizada como plantilla para darle forma a varias páginas web, adaptándola "rápidamente" a cualquier otra presentación en HTML.
    

