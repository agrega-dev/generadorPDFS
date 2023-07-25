# generadorPDFS

Este generador de PDF requiere las siguientes bibliotecas para su instalación:

Itextpdf: Biblioteca para manipular archivos PDF en Java.
Opencsv: Biblioteca para leer y escribir archivos CSV en Java.
VfsjFileChosse: Biblioteca para facilitar la elección de archivos en aplicaciones Java.
El proceso de instalación implica descargar el generador de PDF mediante el comando "git clone" y luego instalar las bibliotecas mencionadas anteriormente.

El uso del generador es sencillo, se requiere un archivo llamado "template.pdf" que servirá como base para el formato del PDF generado. El programa tomará la información contenida en los archivos XML y la insertará en el documento vacío dentro del "template.pdf", generando así el PDF final con los detalles proporcionados en los archivos XML.

Es importante asegurarse de tener instaladas las bibliotecas mencionadas y contar con el archivo "template.pdf" en la ubicación adecuada para que el generador funcione correctamente.

Los documentos de pdfs se necesitara una carpeta que contenga 2 capertas dentro llamas OtrosX y puntosX para la generacion del mismo puesto que los archivos XML Los cuales fueron adaptados para generar dichos pdf se requiere que se separe en categorias.

Este generador de PDF puede ser útil para automatizar la generación de documentos con información específica proporcionada en archivos XML, lo que facilita la creación de informes, facturas u otros documentos personalizados.