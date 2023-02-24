# Scripts en python para tareas diarias del mundo real

- ProcesadorImagenes.py
    - Útil para iterar sobre imagenes en un directorio, procesarlas con Pillow y guardarlas en otro. 
    - Recibe como argumentos de linea de comandos:
        - [Path de la carpeta origen] 
        - [Path de destino] 
        - [Formato]

- Texto_to_post.py
    - Itera sobre una serie de archivos de texto contenidos en una carpeta y los envía mediante una solicitud POST a un servicio web.
        -[Path de la carpeta]
        -[Estructura del diccionario]

- Reports+Mail
    - Procesa un Json para realizar un pdf y enviarlo por email