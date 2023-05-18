# Evaluacion-7.1-Trayectorias-en-lazo-abierto
Daniela Berenice Hernández de Vicente - A01735346


**a) ¿Cuál fué el o los parámetros que se modifican para obtener una trayectoria recta? ¿Porqué?**
Se modifica el vector de velocidad lineal, porque es la que nos inidica cuantos pasos o en este caso metros es lo que deseamos que avance nuestro objeto durante la trayectoria.

**b) ¿Cuál fué el o los parámetros que se modifican para obtener una trayectoria curva? ¿Porqué?**
Se modifican ambos vectores, tanto el vector de velocidad angular como el vector de velocidades, ya que evidentemente si le decimos que avance con cierto angulo esto provocara una curva.

**c) ¿Cuál fué el o los parámetros que se modifican para obtener un giro? ¿Porqué?**
Se modifica el vector de velocidad angular, este se modifica en terminos de pi, y este mismo nos indica la cantidad de grados en radianes los cuales queremos que nuestra simulación gire.

**d) ¿Qué papel desempeña el vector del tiempo en la generación de la trayectoria?**
Este tiene un papel fundamental junto con la integral númerica, ya que debe ser proporcional a la cantidad de tiempos de muestreos totales durante cada vector, tanto el angular como el de velocidades, ya que si este contiene más instrucciones con un menor vector de tiempo, la simulacion terminara por omitir instrucciones, mientras que si el vector tiempo es mayor a la cantidad de instrucciones, sencillamente nos marcara un error al correr el codigo.

**e) ¿Cuáles fueron los parámetros que se ajustaron para obtener las dimensiones de las trayectorias deseadas?**
El unico parametro que movi fueron ciertas instrucciones en el vector de velocidades, como consecuencia las demás medidas tienen que modificarse.


# Evaluacion-7.2-Planeación-de-Trayectorias
Daniela Berenice Hernández de Vicente - A01735346

**¿Por qué escogiste esta trayectoria de control?**

Siendo honestos, es en mi opinión la mejor estrategia el código de Differential drive vehicle following waypoints using the Pure Pursuit algorithm, ya que evidentemente al tener los puntos es más facil ingresarlos, ante este código lo único que se modifica es la visión de nuestro carrito, su velocidad angular y lineal, para obtener una mejor visión, giros más pronunciados.

**Imagen Objetivo**
![Foto_Alfredo_Examen](https://github.com/Bere901/Evaluacion-7.1-Trayectorias-en-lazo-abierto/assets/99983026/18f638b5-796f-4e4f-b07f-a322735e9b81)

**Resultados**
![image](https://github.com/Bere901/Evaluacion-7.1-Trayectorias-en-lazo-abierto/assets/99983026/e59ad59e-c7e9-4ba5-9d25-65a197f2c3d9)
