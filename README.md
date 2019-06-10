# Manejo-deDirectorios-y-Archivos
Práctica  sobre el manejo de archivos y directorios a través de una interfaz de usuario


CARRERA: Computación 

ASIGNATURA: Programación  Aplicada

NRO. PRÁCTICA: 06 

TÍTULO PRÁCTICA: Manejo de Directorios y Archivos 

OBJETIVO ALCANZADO: • Conocer y poner en práctica los conceptos aprendidos en clase mediante esta práctica. 
 
                                       ACTIVIDADES DESARROLLADAS 
 
  
1._ Crear un repositorio en GitHub 
 
https://github.com/CarmenBravo20/Manejo-deDirectorios-y-Archivos.git 
![git (2)](https://user-images.githubusercontent.com/49033767/59197894-0e9c0680-8b58-11e9-8c93-ec74be582da7.jpg)


 
 
2._Crear un proyecto en Java 

 ![net (2)](https://user-images.githubusercontent.com/49033767/59198830-4146fe80-8b5a-11e9-8de7-e8aa05ed07f8.jpg)

3._Desarrollar una aplicación donde el cual nos permita: 
Crear un archivo
Crear una carpeta
Renombrar
Eliminar 
Listar
Su última fecha de modificación 
Su tamaño 
Regresar  
 
Interfaz Gráfica 
 
![interfaz (3)](https://user-images.githubusercontent.com/49033767/59198924-6b98bc00-8b5a-11e9-8867-ffa3f3d91898.jpg)


Para empezar primero debemos saber: ¿De que se trata el manejo de archivos? 
 
• El manejo de archivos nos permite guardar los datos o información de una manera permanente en el disco duro de la memoria.
 • Los datos obtenidos se generan mediante cálculos que se ejecutan en el programa y posterior a esto son guardados en variables para el cual poder almacenar en la memoria virtual. 
 
Botón Listar
A qui lo que esta haciendo es que ingrese la ruta y al momento que lo hace , con e trim() hace que elimine los espacios en blancos y posterior a esto llama al método de lista de Archivos. 
![salir (2)](https://user-images.githubusercontent.com/49033767/59199036-a13da500-8b5a-11e9-9fcb-1ebfe60964b5.jpg)

Listar archivos  

Aquí lo que hace es que se pueda seleccionar cada una de las carpetas o archivos que haya en la ruta ingresada. 
![listar (2)](https://user-images.githubusercontent.com/49033767/59199413-81f34780-8b5b-11e9-9e09-f24ad4ccd6be.jpg)

 
Crear un archivo

 Aquí lo que hace es que primero saldrá una ventanita donde le pedirá ingresar el nombre de la nuevo Archivo luego le pedirá que ingrese la ruta de en qué lugar se va a crear el archivo. Después crea un bucle para ver existe un fichero o directorio instanciado a la clase File y si lo hay crea ya el archivo y si no caso contrario dará un error. 
 
![crear jpg21 (2)](https://user-images.githubusercontent.com/49033767/59199102-c03c3700-8b5a-11e9-8c15-5679b96be0e5.jpg)

Renombrar un archivo 

Aquí primero hace que se seleccione en que parte esta, después lo hace que seleccione y al momento de aplastar renombrar le sale una ventana donde que le pide el nombre que desea y después lo controla para ver si el nombre se repite o no. 

![renombrar (2)](https://user-images.githubusercontent.com/49033767/59199126-cfbb8000-8b5a-11e9-8ff2-ed5e0b17424b.jpg)

Crear una carpeta 
 
Aquí lo que hace es que primero saldrá una ventanita donde le pedirá ingresar el nombre de la nueva carpeta luego le pedirá que ingrese la ruta de en qué lugar se va a crear la carpeta. Después crea un bucle para ver existe un fichero o directorio instanciado a la clase File y si lo hay crea ya la carpeta y si no caso contrario dará un error. 
![crearCa (2)](https://user-images.githubusercontent.com/49033767/59199148-dfd35f80-8b5a-11e9-808a-faad885933a2.jpg)


Eliminar

 Aquí lo que hace es primero que seleccione que parte desea eliminar, después si es válido procede a a eliminarlo y si en caso no le va a salir error. 
![eliminar](https://user-images.githubusercontent.com/49033767/59199164-ec57b800-8b5a-11e9-9def-2181fed8e3f2.jpg)

Regresar 

Aquí lo que hace es que ingrese la ruta, luego con el bucle lo recorre. 
![regresar (2)](https://user-images.githubusercontent.com/49033767/59199518-c2eb5c00-8b5b-11e9-928c-66870d37ea60.jpg)

 
Método eliminar con recursividad 

El isDirectory comprueba si es un directorio mismo, luego recorre la lista de carpetas también es necesario pasarle como parámetro a la carpeta dentro de una variable File para que de esta manera eliminar toda la carpeta hasta las subcarpetas que contenga.

![recursivda (2)](https://user-images.githubusercontent.com/49033767/59199557-d5fe2c00-8b5b-11e9-9518-3224e05a8303.jpg)
 
 Lista  de los archivos

 Aquí es para listar cada uno de las carpetas directorios y ocultos, se usó el método hidden que nos sirve para ver si está oculto o no. 
 
![lista archivi (2)](https://user-images.githubusercontent.com/49033767/59199312-45275080-8b5b-11e9-9b9b-53ca8128c023.jpg)

 
Muestra información 
 
Muestra la información de su ruta su tamaño y su última fecha de modificación. 

![Muetra (2)](https://user-images.githubusercontent.com/49033767/59199329-4ce6f500-8b5b-11e9-954f-508dc9ea7009.jpg)

Resultados  

![Resultado (2)](https://user-images.githubusercontent.com/49033767/59199357-5bcda780-8b5b-11e9-9380-ca48297e572a.jpg)

RESULTADO(S) OBTENIDO(S):
Con esta práctica pudimos aclarar más nuestras ideas que en clases estaban confusas.

CONCLUSIONES: Aprendimos a como crear una carpeta, archivos, a como eliminarlos a renombrarlos y que para ellos necesitamos saber los métodos y para que sirve cada uno es decir que función cumplen, y así de esta manera podemos lograr manipular toda la información que se encuentre almacenada. 

RECOMENDACIONES: Saber cómo funciona cada uno de estos métodos de manejo de archivos, para que al momento de realizarlos se nos facilite. 
 
Nombres del Estudiante:   Carmen Bravo 
 
Firma de estudiante:    Carmen Bravo
