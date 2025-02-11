# Valores Booleanos
### ¿Cómo se precentan los datos en una computadora?
En una computadora, los datos se representan con ceros y unos, conocidos como código binario. Los números, letras e imágenes se convierten en estas secuencias de ceros y unos para que la computadora pueda entenderlos. Por ejemplo, la letra "A" se convierte en una serie de ceros y unos, y lo mismo sucede con los números. Las imágenes, por su parte, se dividen en pequeños puntos llamados píxeles, y cada píxel tiene un valor en ceros y unos que representa su color. Así, todo lo que vemos o usamos en una computadora, como texto o fotos, está hecho de estos códigos de ceros y unos.
### ¿Cuántos estados diferentes pueden ser representados por N variables binarias?
Si tienes N variables binarias, cada una puede ser 0 o 1. Entonces, el número de combinaciones posibles de estos 0 y 1 es 2^N. Es decir, si tienes una sola variable, solo puedes tener 2 opciones. Si tienes dos variables, puedes tener 4 combinaciones diferentes. A medida que añades más variables, el número de combinaciones crece rápidamente. Así que, con N variables, puedes representar 2^N combinaciones distintas.
### ¿Cuáles son las unidades de almacenamiento de datos que se utilizan en computación?
Las unidades de almacenamiento de datos en computación se utilizan para medir la cantidad de información que puede ser almacenada en dispositivos electrónicos. Las unidades más comunes son las siguientes, con sus respectivos prefijos:

| Unidad           | Abreviatura | Prefijo      | Cantidad en bytes       |
|------------------|-------------|--------------|-------------------------|
| Bit              | b           | —            | 1 bit                   |
| Byte             | B           | —            | 8 bits                  |
| Kilobyte         | KB          | Kilo (10^3)  | 1,024 bytes             |
| Megabyte         | MB          | Mega (10^6)  | 1,024 kilobytes         |
| Gigabyte         | GB          | Giga (10^9)  | 1,024 megabytes         |
| Terabyte         | TB          | Tera (10^12) | 1,024 gigabytes         |
| Petabyte         | PB          | Peta (10^15) | 1,024 terabytes         |
| Exabyte          | EB          | Exa (10^18)  | 1,024 petabytes         |
| Zettabyte        | ZB          | Zetta (10^21)| 1,024 exabytes          |
| Yottabyte        | YB          | Yotta (10^24)| 1,024 zettabytes        |

Cada unidad es un múltiplo de la unidad anterior, aumentando de forma exponencial.
### Importancia del trabajo de Bool
El trabajo de Bool es fundamental para la computación moderna, ya que permite representar y manipular información en forma de bits, la base del almacenamiento y procesamiento de datos en las computadoras. Gracias a su álgebra, los circuitos y algoritmos informáticos pueden operar de manera eficiente usando operaciones lógicas.
## Conversion de binarios a decimales
- $1010101010_2$: 2+8+32+128+512= 682
- $11111_2$: 2+4+8+16+32= 62
- $10000000_2$: 128= 128
- $100100100_2$:8+64+512= 584
## Conversión de decimales a binarios
- $127_{10}$
- $246_{10}$
- $1025_{10}$
- $354_{10}$
## Datos que se utilizan en los lenguajes de programación
En programación, los lenguajes como C, Java y Python ofrecen diferentes tipos de datos para representar información. A continuación, se detallan los tipos de datos más comunes en cada lenguaje, junto con sus nombres y abreviaturas:

### **Lenguaje C:**

| Tipo de Dato | Abreviatura | Descripción                             |
|--------------|-------------|-----------------------------------------|
| Entero       | `int`       | Números enteros.                        |
| Flotante     | `float`     | Números con punto decimal.              |
| Doble        | `double`    | Números con mayor precisión decimal.    |
| Carácter     | `char`      | Caracteres individuales.                |
| Cadena       | `char[]`    | Secuencias de caracteres (cadenas de texto). |
| Booleano     | `bool`      | Valores lógicos verdadero o falso.      |

### **Lenguaje Java:**

| Tipo de Dato | Abreviatura | Descripción                             |
|--------------|-------------|-----------------------------------------|
| Entero       | `int`       | Números enteros.                        |
| Largo        | `long`      | Números enteros de mayor tamaño.        |
| Flotante     | `float`     | Números con punto decimal.              |
| Doble        | `double`    | Números con mayor precisión decimal.    |
| Carácter     | `char`      | Caracteres individuales.                |
| Cadena       | `String`    | Secuencias de caracteres (cadenas de texto). |
| Booleano     | `boolean`   | Valores lógicos verdadero o falso.      |

### **Lenguaje Python:**

| Tipo de Dato | Abreviatura | Descripción                             |
|--------------|-------------|-----------------------------------------|
| Entero       | `int`       | Números enteros.                        |
| Flotante     | `float`     | Números con punto decimal.              |
| Complejo     | `complex`   | Números complejos.                      |
| Cadena       | `str`       | Secuencias de caracteres (cadenas de texto). |
| Booleano     | `bool`      | Valores lógicos verdadero o falso.      |


Cada lenguaje tiene sus particularidades en la implementación y uso de estos tipos de datos, lo que influye en la forma en que se manejan y manipulan los datos en los programas. 

### **Organizacion de los datos:**
Aquí tienes una tabla organizada con los tipos de datos de los lenguajes de programación C, Java y Python, que incluye el nombre de la variable, la abreviatura (si existe) y sus características principales:

| **Nombre de la Variable** | **Abreviación** | **Características Principales**                                   |
|---------------------------|-----------------|--------------------------------------------------------------------|
| **Entero**                | `int`           | Números enteros, valores sin decimales. Rango depende del sistema. |
| **Flotante**              | `float`         | Números con punto decimal, precisión limitada.                     |
| **Doble**                 | `double`        | Números con punto decimal de mayor precisión que `float`.           |
| **Largo**                 | `long`          | Enteros de mayor tamaño, usado para números muy grandes.           |
| **Carácter**              | `char`          | Representa un solo carácter (letra, símbolo o número).             |
| **Cadena**                | `char[]`        | Arreglo de caracteres, usado para representar texto.               |
| **Cadena (Java/Python)**  | `String` (`str` en Python) | Secuencias de caracteres.                                        |
| **Booleano**              | `bool`          | Valores lógicos: `true` o `false`.                                 |
| **Complejo**              | `complex`       | Números complejos (solo en Python). Representa parte real e imaginaria. |

### Características adicionales:
- En **C**, las cadenas son representadas como arreglos de caracteres (`char[]`).
- **Java** utiliza `String` para cadenas de texto y tiene un tipo `boolean` para valores lógicos.
- En **Python**, además de `int`, `float` y `bool`, se tiene el tipo `complex` para trabajar con números complejos.
## Ejercicio de calculo de memoria
