# Trabajo de aprendizaje por refuerzo
### Calificado con un 10.

Fork del repositorio para el trabajo en grupo de la asignatura de Inteligencia Artificial 2019-2020, por José Manuel Rojas Granado y Javier Solís García.

## Contenido:

- Notebook con el código del proyecto: Trabajo.ipynb
- Documento realizado con explicación del código e investigación de los algoritmos utilizados: Estudio_Q-learning.pdf
- El resto de archivos son para cargar datos

## Modo de uso:


Vamos a ejecutar, por ejemplo, el algoritmo Q Leaning fase
1 sobre el tablero de ejemplo que nos propone el enunciado:
Primero abrimos el notebook “Trabajo IA”, que es donde
se ha hecho la implementacion del algoritmo. Una vez abierto 
ejecutamos todas las celdas y nos vamos a la parte de abajo
del notebook a la seccion llamada  “Main”. Esta es la parte
que ejecuta el programa. Si le hemos dado a ejecutar todas las
celdas nos iran apareciendo, debajo de este bloque, un formu- 
lario para que indiquemos los datos de entrada al algoritmo.
Es aquı donde debemos indicarle los siguientes parametros: 

- Si queremos cargar nuestra matriz de recompensas le
indicamos un 1, o queremos que se autogenere un 0.

- Casilla de inicio.

- Casilla objetivo.

- Numero de  epocas. 

- El valor del factor de aprendizaje γ.

- El nombre del fichero donde esta el tablero que se quiere cargar (sin extension). 

- Si hemos especificado que queremos cargar nuestra matriz de recompensas, ahora debemos indicarle el nombre del fichero (sin extension). 

- Si queremos que se muestren los caminos intermedios le indicamos un 1, sino un 0.

- El algoritmo que queremos que ejecute, si queremos ejecutar el Q Learning fase 1 (sin los parametros alpha y gamma) le indicamos un 1, si queremos que ejecute el algoritmo
Q Learning fase 2 le indicamos un 2 y si queremos ejecutar el algoritmo ”SARSA” le indicamos un 3.

- El valor del parametro epsilon y alpha, ambos entre 0 y 1 (los decimales se indican con un punto no con una coma).

### Cómo replicar la prueba 1 del PDF:

Estos son los valores de los parametros que hay que usar para replicar la prueba 1:

1. Autogenerar R -> 0

2. Casilla de inicio -> 0

3. Casilla objetivo -> 6

4. Episodios de entrenamiento -> 20

5. gamma -> 0’5

6. Nombre del fichero del tablero -> ejemplo

7. Caminos intermedios -> 1

8. Algoritmo -> 1

***NOTA: Esto también se encuentra explicado de forma más extendida en el documento PDF.***
