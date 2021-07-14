# Proyecto4

En este proyecto se hará una simulación de un sistema de comunicaciones con modulación digital tipo IQ. Para ello se utiliza la modulación BPSK que luego se modificará al tipo 16-QAM, también se evalúa la ergodicidad y estacionaridad de la señal que se modula. Por último se hace la gráfica de la densidad espectral de potencia de la misma señal. Para la modificación de BPSK a 16-QAM se aplico el mismo proceso pero con dos portadoras distintas, una con seno y otra con coseno.

Se simularon y sacaron los promedios a partir de los cuatros posibles casos de ondas que se podían obtener a partir de las variables aleatorias del tipo Bernoulli.

# Conclusiones

## Comparativa de las imágenes recuparadas

Se toma la imagen presentada por el profesor del volcan arenal, se va a trabajar con la misma. 

![arenal](https://user-images.githubusercontent.com/65052436/125574786-118f36ca-4e1b-4692-bd47-76f1d7bf8a25.jpg)

Ahora al aplicar el proceso de modulación 16QAM, se recupera una imagen sumamente similar a la imagen de entrada, con algunos erroes, sin embargo esto es de esperar, debido a que el proceso de modulación no es perfecto. Habría que jugar con los parámetros de forma que el sistema sea más robusto, o bien cambiar la implementación del método de modulación.

También, se hizo una prueba, con una foto en full HD, con el fin de ver que si bien la cantidad de errores es mayor por el tamaño de la foto, el error se distrubuye en toda la foto y por ende entre más grande sea la foto, menos se nota el error. En la foto del Profesor, se notan puntos morados debido a la baja resolución de la misma. 

Los resultados comparativos son los siguientes:

![output](https://user-images.githubusercontent.com/65052436/125576620-f9fc2322-4fb9-43fe-806a-c144e57bcb4a.png)

![output](https://user-images.githubusercontent.com/65052436/125576436-6509f1b6-4a8d-4141-b3b4-5cc92e2a10a4.png)

Como se observa en la siguiente imagen es tan grande que el error no se nota, hay que ver muy detenidamente las nubes para ver que se pierde ''resolución'' 

![output](https://user-images.githubusercontent.com/65052436/125576327-87423673-c2b4-4710-8ba6-24a98b046ad1.png)

![output](https://user-images.githubusercontent.com/65052436/125576561-a0687747-3134-4493-a3a4-4f09ce2cb1f1.png)

## Ergodicidad

Se puede observar que la media es constante en todo momento y que la autocorrelación es dependiente en todo momento del diferencial temporal.

Por lo anterior se puede decir que sí hay estacionaridad y luego se tendría que el proceso es ergódico dado que las medias estadisticas igualan a las temporales.

![output](https://user-images.githubusercontent.com/65052436/125576920-7bc9f501-d94e-4171-b81f-38a81a160b97.png)

## Densidad

Se tiene que la mayoría de valores se encuentran alrededor de la frecuencia de las portadoras, que haya más de una portadora no afecta, ya que el número de simbolos se mantiene dado que se usan dos bits por cada simbolo.

![output](https://user-images.githubusercontent.com/65052436/125576797-48713770-2c87-4c52-8660-16d8a46f0d58.png)

Al final, este proyecto sirve como una pequeña introducción al mundo de las telecomunicaciones
