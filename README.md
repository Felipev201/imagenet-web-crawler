# Actividad Integradora #2
##### Esta actividad contiene un raspador web que extrae imágenes específicas de la base de datos [ImageNet](http://www.image-net.org/), en base a un término de busqueda ingresado por el usuario. Divide las imágenes descargadas en dos carpetas. El 80% de las imágenes se guardan en una carpeta de entrenamiento y un 20% en una carpeta de pruebas. 

Utilizando el entorno de pruebas Selenium en conjunto con las librerías NumPy, OpenCV y sci-kit image, el programa abre una pestaña de Chrome utilizando Selenium y Chromedriver, introduciendo en la barra de búsqueda del sitio principal el termino específicado por el usuario. Tras realizar la busqueda, el programa extrae los URLs correspondientes guardándolos en una lista. A partir de la lista de URLs, se realiza la división de los datos en un set de entrenamiento (80% de los resultados) y de pruebas (20% de los resultados). En base a estas listas, se guardan los resultados obtenidos en su carpeta correspondiente, guardando las imágenes con ayuda de sci-kit image. 

El código en el jupyter notebook, muestra los URLs minados, así como aquellos que son descargados. 

Consideramos en base al programa y su presentación que presentaría un buen punto de partida para aquellos interesados en desarrollar un web scraper de imágenes, partícularmente en el ámbito de inteligencia artificial.

##### Representación y fuente de datos. 
Las imágenes utilizadas son extraídas de la base de datos [ImageNet](http://www.image-net.org/) utilizando la herramienta [Selenium](https://selenium-python.readthedocs.io/).

##### Dependencias 
1. Selenium
2. OpenCV
3. Numpy
4. Sci-kit image (en partícular el módulo io)

##### Algoritmo

