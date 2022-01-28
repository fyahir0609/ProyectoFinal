# ProyectoFinal
Webscraper

Integrantes:
Fernández Sánchez Yahir Sebastián


Instrucciones:

Primeramente lo que debemos hacer es cambiar la ruta de nuestra variable "path" que aparece en las funciones "Buscador_Precios_Selenium_PalaciodeHierro(producto)","Buscador_Precios_Selenium_Sanborns(producto)", "Buscador_Precios_Selenium_BA(producto)", a la dirección en donde se ubica el webdriver en el ordenador.

Posterior a lo anterior es necesario tener en consideración que debemos ejecutar nuestro codigo por partes, la primera parte debemos ejecutarla de la linea 1 a la linea 305 (parte del codigo correspondiente a las funciones), esto es necesario porque primero debemos de generar el excel y almacenar el dataframe que se generara con las funciones realizadas. Seguido de esto una vez que se haya generado el excel debemos buscar este mismo en nuestro ordenador y obtener su correspondiente ruta, la cual deberemos de modificar en la variable "archivo" que se encuentra almacenada en la linea 309

