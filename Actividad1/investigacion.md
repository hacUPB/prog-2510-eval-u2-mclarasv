# <span style="color: aqua">Computadores</span>
## ¿Qué es un computador?
"Máquina electrónica capaz de realizar un tratamiento automático de la información y de resolver con gran rapidez problemas matemáticos y lógicos mediante programas informáticos".  sacado de: https://www.rae.es/dpd/computador
## Arquitectura de un computador
La arquitectura de una computadora es el diseño y organización de sus componentes principales, como la CPU, la memoria, los dispositivos de entrada/salida y el sistema de buses, que trabajan juntos para ejecutar programas y procesar datos. Determina cómo estos elementos interactúan entre sí para realizar tareas de manera eficiente.
### Arquitura CISC:
La arquitectura CISC es un tipo de diseño de procesador que usa instrucciones complejas para hacer muchas cosas con una sola orden. Esto significa que una sola instrucción puede realizar varias tareas al mismo tiempo, como sumar y almacenar datos, lo que reduce la cantidad de instrucciones necesarias para ejecutar un programa.
### Arquitectura RISC:
La arquitectura RISC es un tipo de diseño de procesador que utiliza un conjunto de instrucciones simples y rápidas. Cada instrucción realiza una sola tarea en un solo ciclo de reloj, lo que hace que el procesamiento sea más eficiente y rápido, aunque se necesiten más instrucciones para realizar tareas complejas.
## ¿Qué es el hardward?
El hardware es la parte física de una computadora o sistema informático, que incluye todos los componentes que se pueden tocar y ver. Estos componentes son los encargados de ejecutar las instrucciones y almacenar datos.
### CPU:
La CPU es el cerebro de la computadora, responsable de ejecutar las instrucciones de los programas. Realiza operaciones aritméticas, lógicas y de control, y coordina el funcionamiento del resto de los componentes.
Partes importantes de la CPU:
#### ALU: 
Realiza operaciones matemáticas (como sumas y restas) y lógicas (como AND, OR).
#### Unidad de control:
Se encarga de interpretar las instrucciones del programa y coordinar la actividad de la CPU, enviando señales de control a otras partes del sistema.
#### Registros:
Son pequeñas unidades de almacenamiento dentro de la CPU que guardan temporalmente los datos que están siendo procesados.
#### Buses:
Son canales de comunicación que transportan datos entre la CPU, la memoria y otros componentes. Existen varios tipos de buses: de datos, de direcciones y de control.
###  GPU
La GPU es un procesador especializado en el manejo de gráficos y procesamiento paralelo, como los que se usan en videojuegos, renderizado de imágenes y aprendizaje automático.

#### ¿Cómo funciona?
La GPU está diseñada para realizar muchas operaciones en paralelo, lo que la hace ideal para procesar gráficos y manejar tareas que requieren gran capacidad de cálculo, como el procesamiento de imágenes o la ejecución de algoritmos de inteligencia artificial.

#### Comparación con la CPU:
**CPU:** Está diseñada para manejar tareas generales de procesamiento, con pocos núcleos pero de alta potencia para tareas complejas secuenciales.

**GPU:** Está optimizada para tareas paralelizadas, con muchos núcleos que ejecutan operaciones simples a la vez, ideal para gráficos y grandes volúmenes de datos.

#### Diferencias:
La CPU se enfoca en tareas generales, mientras que la GPU se especializa en tareas gráficas y de cómputo paralelo.
La CPU tiene menos núcleos, pero más potentes, mientras que la GPU tiene más núcleos, pero con menor poder individual.

### Memoria:
La memoria se utiliza para almacenar datos y programas que está utilizando la computadora. Existen diferentes tipos de memoria según la rapidez y la cantidad de almacenamiento.

#### Tipos de memoria:
##### Registros:
Son pequeños espacios de memoria dentro de la CPU que almacenan datos temporales de uso inmediato. Son muy rápidos.
##### Caché:
Es una memoria de acceso ultra rápido que guarda datos e instrucciones de uso frecuente para que la CPU los acceda rápidamente. Suele estar dividida en varios niveles (L1, L2, L3), con L1 siendo la más rápida y cercana al procesador.
##### Memoria Principal (RAM):
Es la memoria de trabajo que almacena los datos y programas en ejecución. Es volátil, es decir, se borra cuando se apaga la computadora.
##### Memoria Secundaria (Disco duro, SSD y unidades externas):
Son dispositivos de almacenamiento permanente. El disco duro (HDD) es más lento y tiene mayor capacidad, mientras que los SSDs son más rápidos y resistentes. Las unidades externas (como USB o discos externos) proporcionan almacenamiento adicional y portátil.

### Dispositivos de Entrada/Salida (E/S):
Son los componentes que permiten la interacción entre el usuario y la computadora, permitiendo la entrada y salida de datos.

#### Ejemplos:
##### Entrada: 
Teclado, ratón, micrófono, cámara, escáner.
##### Salida: 
Monitor, impresora, altavoces.

También existen dispositivos que funcionan como entrada y salida, como las pantallas táctiles.

### Buses de Datos:
Los buses de datos son canales de comunicación que transportan los datos entre la CPU, la memoria y otros dispositivos de la computadora. Los buses se encargan de transportar la información de un lugar a otro dentro de la máquina.

#### Tipos de Buses:
##### Bus de datos: 
Transporta los datos reales entre los componentes.
##### Bus de direcciones: 
Lleva las direcciones de memoria desde la CPU hasta la memoria o los dispositivos.
##### Bus de control: 
Transporta señales que indican la dirección de los datos y las operaciones que deben realizarse.

## ¿Qué es el softward?
El software es el conjunto de programas que permiten que una computadora funcione. Se clasifica en tres tipos:

### Software de sistema:
Controla el hardware y permite que la computadora funcione, como el sistema operativo.
### Software de aplicación: 
Son los programas que usamos para realizar tareas específicas, como Word, Excel o navegadores.
### Software de desarrollo: 
Herramientas para crear otros programas, como lenguajes de programación o entornos de desarrollo.
## Funcionamiento del computador:
### Procesos al encender una computadora:
#### POST (Power-On Self-Test): 
La computadora realiza una revisión básica del hardware para asegurarse de que todos los componentes (memoria, procesador, etc.) estén funcionando correctamente.
#### Carga del BIOS/UEFI: 
El BIOS/UEFI, que es el software básico de inicio, se encarga de inicializar el hardware y cargar el sistema operativo.
#### Arranque del sistema operativo: 
Se carga el sistema operativo desde el disco duro o SSD y prepara la computadora para que el usuario pueda interactuar con ella.

### Proceso de ingreso de un dato hasta ver el resultado en pantalla:
#### Ingreso de dato: 
Cuando presionas una tecla, el teclado envía una señal al procesador.
#### Procesamiento: 
El procesador recibe el dato y lo procesa de acuerdo con el programa o la operación que esté en ejecución.
#### Resultado: 
El procesador envía el resultado al monitor, que lo muestra en forma de texto, gráficos o imágenes.
### Codificación de los datos internamente en el computador:
Los datos se codifican en binario. Es decir, se representan mediante combinaciones de 0s y 1s (bits), que es el lenguaje que entiende la computadora. Los caracteres, imágenes y otros datos se convierten a este formato binario para ser almacenados y procesados.
### Unidades de medida de datos:
#### Bit (b): 
Es la unidad más pequeña de datos y puede tener solo dos valores: 0 o 1.
#### Byte (B): 
Equivale a 8 bits. Es la cantidad de datos suficiente para representar un solo carácter (como una letra o número).
#### Kilobyte (KB): 
1,024 bytes.
#### Megabyte (MB): 
1,024 kilobytes.
#### Gigabyte (GB): 
1,024 megabytes.
#### Terabyte (TB): 
1,024 gigabytes.