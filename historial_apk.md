### Historial de apk's OSMTracker

#### Primera versión colocada en las pruebas beta:  
Características:
- Funcionalidad de activar/instalar layouts desde una actividad en específico
- Eliminar layouts: funcionalidad dada a cada layout descargado, a parece en el pop-menu luego de una presión larga sobre uno de los layouts
- Actualización: funcionalidad de volver a descargar el layout desde el servidor actual, reescribiendo los datos del layout descargado
- Ir a la actividad de Layouts Disponibles: si no existe una conexión de internet aparace un toast con el mensaje de que no hay conexión disponible
- Cargar los layout del repositorio: se muestra en pantalla los layouts que existen en el repositorio actual, en forma de un texto sin diseño alguno
- Comprobación del idioma: una vez se presiona sobre el layout a descargar se comprueba si el idioma local coinciden con alguno de los idiomas del layout, si no, se muestra un diálogo con los idiomas disponibles
- Mostrar la descripción: se muestra la descripción (en el idioma local o en el idioma por defecto del layout)
- descargar layout (junto con los iconos y el metadata)
- cambiar opciones de repositorio Github

### Segunda versión de las pruebas beta:  
Características:
- En la actividad de Layouts Disponibles se modifica la interfaz, en vez de usar textos planos se utilizan botones separados 
para cada layout
- Se mejora la forma de borrar un layout, ya no se cierra y abre la actividad, ahora se refresca, haciendo que la acción sea más
natural visualmente
- Se agrega un diálogo a la hora de actualizar con un mensaje de "Updating..." (Las traducciones al español están en proceso para la siguiente versión)
- Tambien se agrega un diálogo cuando se comprueba el idioma local
- A la hora de descargar también aparece un diálogo mientras se realiza la descarga ("Downloading...")

### Tercera versión de las pruebas beta:  
Características:
- Se quitan algunos toast innecesarios, como los de la descarga, ahora muestran un mensaje más coherente 
- Se agrega el mensaje "Usted no tiene layouts descargados aún" cuando se borran todos los layouts
- Se agregan las traducciones a español

### Cosas por hacer:
- A la hora de presionar el "Custom Checkbox" en "Github Repository Settings" quitar la funcionalidad de borrar (Esto solo pasa cuando se inicia la aplicación por primera vez o se hace uso de esta funcionalidad por primera vez, las demás veces se autocompleta con los datos guardados anteriormente).
