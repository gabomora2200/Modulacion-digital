# Proyecto4

En este proyecto se hará una simulación de un sistema de comunicaciones con modulación digital tipo IQ. Para ello se utiliza la modulación BPSK que luego se modificará al tipo 16-QAM, también se evalúa la ergodicidad y estacionaridad de la señal que se modula. Por último se hace la gráfica de la densidad espectral de potencia de la misma señal. Para la modificación de BPSK a 16-QAM se aplico el mismo proceso pero con dos portadoras distintas, una con seno y otra con coseno.

Se simularon y sacaron los promedios a partir de los cuatros posibles casos de ondas que se podían obtener a partir de las variables aleatorias del tipo Bernoulli.

# Conclusiones

Se toma la imagen presentada por el profesor del volcan arenal, se va a trabajar con la misma. 

![arenal](https://user-images.githubusercontent.com/65052436/125574786-118f36ca-4e1b-4692-bd47-76f1d7bf8a25.jpg)

Ahora al aplicar el proceso de modulación 16QAM, se recupera una imagen sumamente similar a la imagen de entrada, con algunos erroes, sin embargo esto es de esperar, debido a que el proceso de modulación no es perfecto. Habría que jugar con los parámetros de forma que el sistema sea más robusto, o bien cambiar la implementación del método de modulación.

También, se hizo una prueba, con una foto en full HD, con el fin de ver que si bien la cantidad de errores es mayor por el tamaño de la foto, el error se distrubuye en toda la foto y por ende entre más grande sea la foto, menos se nota el error. En la foto del Profesor, se notan puntos morados debido a la baja resolución de la misma. 

Los resultados comparativos son los siguientes:

![Figure_1](https://user-images.githubusercontent.com/65052436/125575618-7cb7db6a-b413-4778-887d-ab68d7f36b33.png)
