Proyecto Reconocimiento de caras y edición de imágenes con OpenCV y Processing
Alfredo del Val Ramos, 2º BACH B

(Video demostración: https://youtu.be/srKGIxRuMZA)

El objetivo fundamental de este proyecto es el poder conseguir editar la imagen que se recoge de la webcam para poder reconocer caras y poner imágenes sobre estas. 
Para ello he comenzado con dos programaciones base:

•	La primera se basa en poner fotos sobre las caras reconocidas en una imagen fija. En este caso hemos puesto un equipo de futbol al cual hemos reconocido las caras y posteriormente añadido otra foto de una cara de otra persona.
Las principales funciones a destacar de este programa son:
o	opencv.detect() Función de la librería OpenCV que detecta automáticamente las caras de nuestras fotos.
o	imagen.resize() Función que nos ayudará a escalar la foto con la que sustituiremos la cara para que esta tenga un tamaño apropiado.
o	image() Función para poner determinada imagen en determinadas coordenadas.

•	El objetivo del segundo programa se basa en capturar la imagen de la webcam y posteriormente reconocer las caras y remárcalas con un recuadro. Cabe recalcar que esta ha sido la programación que mas fallos ha dado ya que la mayoría de las veces este programa no reconoce la webcam.
Las principales funciones a destacar de este programa son:
o	opencv.loadImage(Capture) Con esta función podremos poner la camara como si se tratase de una imagen y poder trabajar con ella cómodamente. 
o	A recalcar el bucle for con el cual haremos los rectángulos de las caras.

•	En la programación final juntamos lo aprendido anteriormente, primero incorporamos la transmisión de la cámara al programa (aprendido en la 2ª programación). Luego incorporaremos el sistema de poner imágenes en los rostros de la 1ª programación. Así obtendremos el resultado final del proyecto.

•	Todos los archivo, programaciones y vides de demostración están subidos en este GitHub.

