# Comentarios tarea 02

### Clasificador de temperatura
El primer problema fue desarrollado en clases en conjunto con las profesoras, por lo que se me hizo súper llevadera la elaboración del código. 

Primero cree un notebook en Google Colab en el cual cree una lista de números que van desde el -30 hasta el 50, el cual se consideró en el código del -30 al 51, porque en computación el primer valor es 0.

Para aquellos números negativos, el programa debe mostrar el mensaje "Muy frío"; para los números del 0 al 24, el mensaje debe mostrar "Templado"; y para aquellos mayores o igual a 25, el mensaje "Caluroso".

### Números especiales del robot
Agregué en el mismo proyecto el apartado de "+ Código" para escribir el segundo problema en el mismo notebook. Para este problema seguí la misma lógica que en el primero. 

Cree una lista de números que van desde el 1 al 100, el cuál se consideró en el código del 1 al 101. Para aquellos números que sean divisibles por 10, el programa debe mostrar el mensaje "Bip Bip", y para aquellos números que sean divisibles por 5, el programa debe mostrar el mensaje "Bip".

A comparación del problema 1, solo tuve que cambiar el rango de los datos y en la parte de "elif" agregar "x % 5 == 0:" para que fuera divisible por 5 y así se imprimera "Bip" en los números correspondientes.

### Detector de puntaje gamer
Agregué otro código al notebook y me guié por las indicaciones que las profesoras dieron en la última clase, donde se deben sumar las variables. En este caso fueron "suma = puntaje1 + puntaje2". 

El resultado de la suma revela el nivel de gamer que eres: si la suma de los dos puntajes es menor a 50, eres "Nivel principiante"; si la suma es mayor o igual a 50 pero menor que 80, eres "Nivel Intermedio"; y si la suma es mayor o igual a 80, eres "Nivel pro".

Fue gratificante ver que funcionó el código y podía agregar el puntaje en las casillas, obteniendo diversos resultados según los números que se coloquen.

### Calculador musical
Finalmente, se agregó otro apartado para el código y en este si tuve que pedir ayuda a la inteligencia artificial Claude, mencionada por ustedes en clases. Le expliqué lo que estabamos haciendo en general y le mandé el ejemplo de las temperaturas del problema 1 para que entendiera la lógica. 
A Claude solo le solicité ayuda porque no entendía cómo hacer los parámetros, sin embargo, no le pedí el código en sí.
Claude me guió y entendí que debía seguir los mismos pasos que en el problema 3, sólo que las dos variables (música y baile) no son números sino respuestas de sí y no. 

![Instrucción](Claude.png)

En base a ello, fui escribiendo el código, siguiendo la estructura similar del problema 3. El programa solicita la edad de la persona y en base a las preguntas "¿Te gusta la música?" y "¿Te gusta bailar?" y sus respectivas respuestas, te da un resultado. Para aquellas personas de 18 años o más que responden "si" en ambas casillas, el resultado es "Eres una estrella de la fiesta"; Para aquellos que le gusta la música pero no bailar, el resultado es "Te gusta la música, pero no tanto bailar"; y para aquellos que no cumplan con ninguna de las dos condiciones anteriores, el resultado es "Tienes tu propio estilo".

Finalmente resultó el código y también fue muy gratificante ver sus respuestas.