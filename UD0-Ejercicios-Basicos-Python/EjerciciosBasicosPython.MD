- [1. Ejercicios Básicos de Python](#1-ejercicios-básicos-de-python)
  - [1.1. Entrada/salida de datos - Variables - Tipos de datos](#11-entradasalida-de-datos---variables---tipos-de-datos)
  - [1.2. Blucles - Selección - Repeticiones](#12-blucles---selección---repeticiones)
  - [1.3. Funciones](#13-funciones)
- [2. Referencias](#2-referencias)

# 1. Ejercicios Básicos de Python
## 1.1. Entrada/salida de datos - Variables - Tipos de datos  

 **1.** Escribe un programa que solicite al usuario que ingrese su nombre. El nombre se debe almacenar en una variable llamada nombre. A continuación se debe mostrar en  pantalla el texto “Ahora estás en Matrix, [usuario]”, donde “[usuario]” se reemplazará por el nombre que el usuario haya ingresado.

 **2.** Escribe un programa que solicite al usuario ingresar un número con decimales y almacenalo en una variable. A continuación, el programa debe solicitar al usuario que ingrese un número entero y guardarlo en otra variable. En una tercera variable se deberá guardar el resultado de la suma de los dos números ingresados por el usuario. Por último, se debe mostrar en pantalla el texto “El resultado de la suma es [suma]”, donde “[suma]” se reemplazará por el resultado de la operación.

 **3.** Escribe un programa que solicite al usuario dos números y los almacene en dos variables. En otra variable, almacená el resultado de la suma de esos dos números y luego mostrá ese resultado en pantalla.
A continuación, el programa debe solicitar al usuario que ingrese un tercer número, el cual se debe almacenar en una nueva variable. Por último, mostrá en pantalla el resultado de la multiplicación de este nuevo número por el resultado de la suma anterior.

**4.** Escribe un programa que solicite al usuario ingresar la cantidad de kilómetros recorridos por una motocicleta y la cantidad de litros de combustible que consumió durante ese recorrido. Mostrar el consumo de combustible por kilómetro.

**5.** Escribe un programa que solicite al usuario el ingreso de una temperatura en escala Fahrenheit (debe permitir decimales) y le muestre el equivalente en grados Celsius. La fórmula de conversión que se usa para este cálculo es: _Celsius = (5/9) * (Fahrenheit-32)

**6.** Escribe un programa que solicite al usuario ingresar tres números para luego mostrarle el promedio de los tres.

**7.** Escribe un programa que solicite al usuario el ingreso de un texto y almacene ese texto en una variable. A continuación, mostrar en pantalla la primera letra del texto ingresado. Luego, solicitar al usuario que ingrese un número positivo menor a la cantidad de caracteres que tiene el texto que ingresó (por ejemplo, si escribió la palabra “HOLA”, tendrá que ser un número entre 0 y 4) y almacenar este número en una variable llamada indice.
Mostrar en pantalla el carácter del texto ubicado en la posición dada por indice.

**8.** Escribe un programa que solicite al usuario que ingrese cuántos shows musicales ha visto en el último año y almacene ese número en una variable. A continuación mostrar en pantalla un valor de verdad (True o False) que indique si el usuario ha visto más de 3 shows.

**10.** Escribe un programa que solicite al usuario que ingrese cuántos shows musicales ha visto en el último año y almacene ese número en una variable. A continuación mostrar en pantalla un valor de verdad (True o False) que indique si el usuario ha visto más de 3 shows.
 
>Ejemplo de ejecución:
```shell 
Shows vistos en el último año: 3
False
```
**11.**  Escribe un programa que le solicite al usuario ingresar una fecha formada por 8 números, donde los primeros dos representan el día, los siguientes dos el mes y los últimos cuatro el año (DDMMAAAA). Este dato debe guardarse en una variable con tipo int (número entero). Finalmente, mostrar al usuario la fecha con el formato DD / MM / AAAA.

>Ejemplo de ejecución:
```shell
Fecha en formato DDMMAAAA: 16112017
16 / 11 / 2017
```

**12.** Escribe un programa para solicitar al usuario el ingreso de un número entero y que luego imprima un valor de verdad dependiendo de si el número es par o no. Recordar que un número es par si el resto, al dividirlo por 2, es 0.
 
>Ejemplo de ejecución:
```shell 
Número entero: 7254
```
**13.** Escribe un programa que le solicite al usuario su edad y la guarde en una variable. Que luego solicite la cantidad de artículos comprados en una tienda y la guarde en otra variable. Finalmente, mostrar en pantalla un valor de verdad (True o False) que indique si el usuario es mayor de 18 años de edad y además compró más de 1 artículo.
 
>Ejemplo de ejecución:
```shell 
Tu edad: 32
Artículos comprados: 1
False
```

**14.** Escribe un programa que, dada una cadena de texto por el usuario, imprima True si la cantidad de caracteres en la cadena es un número par, o False si no lo es.
 
>Ejemplo de ejecución:
```shell 

Escribe una frase: Era el mejor de los tiempos, era el peor de los tiempos.
True
```
15. Escribe un programa que le pida al usuario ingresar dos palabras y las guarde en dos variables, y que luego imprima True si la primera palabra es menor que la segunda o False si no lo es.
 
>Ejemplo de ejecución:
```shell 

Una palabra: complejidad
Otra palabra: algoritmo
False

16
Escribe un programa para pedir al usuario su nombre y luego el nombre de otra persona, almacenando cada nombre en una variable. Luego mostrar en pantalla un valor de verdad que indique si: los nombres de ambas personas comienzan con la misma letra ó si terminan con la misma letra. Por ejemplo, si los nombres ingresados son María y Marcos, se mostrará True, ya que ambos comienzan con la misma letra. Si los nombres son Ricardo y Gonzalo se mostrará True, ya que ambos terminan con la misma letra. Si los nombres son Florencia y Lautaro se mostrará False, ya que no coinciden ni la primera ni la última letra.
 
>Ejemplo de ejecución:
```shell 

Tu nombre: Alfredo
Otro nombre: Eduardo
True
```

## 1.2. Blucles - Selección - Repeticiones  

```
**17.** Escribe un programa que, dado un número entero, muestre su valor absoluto. Recordá que, para los números positivos su valor absoluto es igual al número (el valor absoluto de 52 es 52), mientras que, para los negativos, su valor absoluto es el número multiplicado por -1 (el valor absoluto de -52 es 52).
 
>Ejemplo de ejecución:
```shell 

Número: -12
Valor absoluto: 12
```
**18.** Escribe un programa que solicite al usuario el ingreso de dos números diferentes y muestre en pantalla al mayor de los dos.
 
>Ejemplo de ejecución:
```shell 
Un número: 592
Otro número distinto: 1726
1726 es mayor
```
**19.** Escribe un programa que solicite al usuario una letra y, si es una vocal, muestre el mensaje “Es vocal”. Verificar si el usuario ingresó un string de más de un carácter y, en ese caso, informarle que no se puede procesar el dato.
 
>Ejemplo de ejecución:
```shell 
Letra: o
Es vocal
```
**20.** Escribe un programa para solicitar al usuario tres números y mostrar en pantalla al menor de los tres.
 
>Ejemplo de ejecución:
```shell 
Primer número: 20
Segundo número: 30
Tercer número: 10
Menor: 10
```

**21.** Escribe un programa que solicite ingresar un nombre de usuario y una contraseña. Si el nombre es “Gwenevere” y la contraseña es “excalibur”, mostrar en pantalla “Usuario y contraseña correctos. Puede ingresar a Camelot”. Si el nombre o la contraseña no coinciden, mostrar “Acceso denegado”.
 
>Ejemplo de ejecución:
```shell 
Nombre de usuario: gwen
Contraseña: excalibur
Acceso denegado
```

**22.** Escribe un programa que permita saber si un año es bisiesto. Para que un año sea bisiesto debe ser divisible por 4 y no debe ser divisible por 100, excepto que también sea divisible por 400.
 
>Ejemplo de ejecución:
```shell 
Año: 2020
Bisiesto
```

**23.** Escribe un programa que le solicite al usuario un número entero y muestre todos los números correlativos entre el 1 y el número ingresado por el usuario.
 
>Ejemplo de ejecución:
```shell 
Ingresá un número: 3
1
2
3
```

**24.** Escribe un programa que muestre la sumatoria de todos los números entre el 0 y el 100.
 
>Ejemplo de ejecución:
```shell 
Sumatoria: 5050
```

**25.** Escribe un programa que, dado un número por el usuario, muestre todos sus divisores positivos. Recordá que un divisor es aquel que divide al número de forma exacta (con resto 0).
 
>Ejemplo de ejecución:
```shell 
Número: 14
Divisores:
1
2
7
14
```

**26.** Escribe un programa que, dada una frase por el usuario, muestre la cantidad total de vocales (tanto mayúsculas como minúsculas) que contiene.
 
>Ejemplo de ejecución:
```shell 
Frase: Verde que te quiero verde
Vocales: 11
```

**27.** Escribe un programa que muestre los primeros 10 números de la sucesión de Fibonacci. La sucesión comienza con los números 0 y 1 y, a partir de éstos, cada elemento es la suma de los dos números anteriores en la secuencia: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55…
 
>Ejemplo de ejecución:
```shell 

0
1
1
2
3
5
8
13
21
34
```
**28.** Escribe un programa que, dado un número entero positivo, calcule y muestre su factorial. El factorial de un número se obtiene multiplicando todos los números enteros positivos que hay entre el 1 y ese número. El factorial de 0 es 1.
 
>Ejemplo de ejecución:
```shell 
Número: 7
Factorial: 5040
```

**29.** Escribe un programa que permita al usuario ingresar 6 números enteros, que pueden ser positivos o negativos. Al finalizar, mostrar la sumatoria de los números negativos y el promedio de los positivos. No olvides que no es posible dividir por cero, por lo que es necesario evitar que el programa arroje un error si no se ingresaron números positivos.
 
>Ejemplo de ejecución:
```shell 

Número: 15
Número: -12
Número: 5
Número: 10
Número: -3
Número: 9
Sumatoria de los negativos: -15
Promedio de los positivos: 9.75
```

**30.** Escribe un programa que permita al usuario ingresar una frase y luego un carácter (string de longitud 1) y luego muestre la frase ingresada, pero con todas las ocurrencias del carácter indicado por el usuario reemplazadas por “*”.
>Ejemplo de ejecución:
```shell
Frase: Aquí me pongo a cantar al compás de la vigüela_
Carácter: o
Aquí me p*ng* a cantar al c*mpás de la vigüela
```

**31.** Escribe un programa que, dada una frase por el usuario, la muestre invertida, sin utilizar una rebanada con paso negativo.
 
>Ejemplo de ejecución:
```shell 

Frase: Sabía quién era esta mañana, pero he cambiado varias veces desde entonces
secnotne edsed secev sairav odaibmac eh orep ,anañam atse are néiuq aíbaS

```

**32.** Escribe un programa que permita al usuario ingresar los montos de las compras de un cliente (se desconoce la cantidad de datos que cargará, la cual puede cambiar en cada ejecución), cortando el ingreso de datos cuando el usuario ingrese el monto 0. Si ingresa un monto negativo, no se debe procesar y se debe pedir que ingrese un nuevo monto. Al finalizar, informar el total a pagar teniendo que cuenta que, si las ventas superan el monto total de 1000, se le debe aplicar un 10% de descuento.
 
>Ejemplo de ejecución:
```shell 

Monto de una venta: $ 100
Monto de una venta: $ 300
Monto de una venta:$ -1
Monto no válido.
Monto de una venta: $ 2000
Monto de una venta: $ 0
Monto total a pagar: $ 2160.0
```

**33.** Escribe un programa que permita al usuario ingresar una cantidad de números positivos indefinida (la cantidad que ingresará no se conoce y puede cambiar en cada ejecución), finalizando cuando ingresa el número 0 (que no se tendrá en cuenta). Una vez terminada la lectura de números, informar cuál fue el mayor de los números ingresados.
 
>Ejemplo de ejecución:
```shell 

Número: 6
Número: 9
Número: 2
Número: 12
Número: 0
Mayor número ingresado: 12
```

**34.** Escribe un programa que pregunte al usuario si desea analizar calificaciones de alumnos y, sólo si responde “S” comenzará el procesamiento de los datos, hasta que el usuario ingrese algo diferente de “S”. Por cada alumno, permitir ingresar su calificación. Si es mayor a 4 el alumno está aprobado. Finalmente, mostrar “Porcentaje de alumnos aprobados: x %” (donde x es el porcentaje de aprobados sobre el total de calificaciones procesadas). También se debe imprimir “Promedio de los aprobados: y” (donde y es la calificación promedio, sólo de los alumnos aprobados).
 
>Ejemplo de ejecución:
```shell 
¿Analizar calificaciones? ‘S’ para ‘sí’: S
Calificación de un alumno: 9
¿Continuar? ‘S’ para ‘sí’: S
Calificación de un alumno: 4
¿Continuar? ‘S’ para ‘sí’: S
Calificación de un alumno: 8
¿Continuar? ‘S’ para ‘sí’: N
Porcentaje de alumnos aprobados: 66.66666666666667 %
Promedio de los aprobados: 8.5
```
**35.** Escribe un programa que solicite al usuario el ingreso de strings de longitud 1 (un solo carácter), uno por vez. La repetición finalizará cuando se ingrese un string que no tenga longitud 1, o cuando el string ingresado corresponda al dígito numérico 0. Al finalizar, mostrar el string completo que se formó con todos los caracteres ingresados y qué porcentaje de caracteres del total fueron la letra “a”.
 
>Ejemplo de ejecución:
```shell 

Escribe un carácter: L
Escribe un carácter: 9
Escribe un carácter: a
Escribe un carácter: 4
Escribe un carácter: A
Escribe un carácter: 0
Escribe un carácter: N
Escribe un carácter: a
Escribe un carácter: a
Escribe un carácter: 5
El string completo es: L9a4A0Naa
Porcentaje de letras ‘a’: 33.333333333333336
```

**36.** Escribe un programa que, dado un número entero por el usuario (guardado como int), muestre la suma de todos sus dígitos. Recordá que vas a necesitar obtener cada uno de los dígitos por separado para poder sumarlos entre sí.
 
>Ejemplo de ejecución:
```shell 

Escribe un número: 7124
Suma de los dígitos: 14
```

**37.** Escribe un programa para solicitar al usuario que ingrese números enteros positivos (la cantidad que ingresará no se conoce y la decide el usuario). La lectura de números finalizará cuando el usuario ingrese el número -1. Por cada número ingresado, mostrar la cantidad de dígitos pares y la cantidad de dígitos impares que tiene. Al finalizar, mostrar cuántos números múltiplos de 3 ingresó el usuario.
 
>Ejemplo de ejecución:
```shell 

Número (-1 para terminar el programa): 123
Dígitos pares: 1
Dígitos impares: 2
Número (-1 para terminar el programa): 44
Dígitos pares: 2
Dígitos impares: 0
Número (-1 para terminar el programa): 9
Dígitos pares: 0
Dígitos impares: 1
Número (-1 para terminar el programa): -1
Se ingresaron 2 múltiplos de 3.
```
**38.** Escribe un programa que solicite al usuario una cadena de caracteres (que puede contener letras, números o símbolos). Analizar la cadena para mostrar: cuántas letras del abecedario (minúsculas y mayúsculas) contiene, cuántos símbolos (caracteres que no son ni letras ni números), cuántos dígitos numéricos y, de los dígitos, cuántos son múltiplos de 4.
 
>Ejemplo de ejecución:
```shell 

Cadena de caracteres: 1984 (novela de George Orwell)
Cantidad de letras: 20
Cantidad de dígitos numéricos: 4
Cantidad de símbolos: 6
Cantidad de múltiplos de 4: 2
```

**39.** Escribe un programa que permita al usuario ingresar números que serán leídos como string (no como int o float) hasta que ingrese uno que sea múltiplo de 10 ó menor que 0 (que no será procesado). Se formarán dos strings, en los cuales se concatenarán los números ingresados, según el siguiente criterio: en un string se concatenarán todos los números que el usuario ingrese cuya cantidad de dígitos sea un múltiplo de 3. En el otro, se concatenarán todos los números que contengan el dígito 0. Si un número cumple ambas condiciones, debe concatenarse en ambos strings. En cada string, después de cada número concatenado debe colocarse el carácter “-”. Al finalizar, mostrar en pantalla ambos strings.
 
>Ejemplo de ejecución:
```shell 
Número: 829
Número: 102834
Número: 6
Número: 4307
Número: 23
Número: 1602357
Número: 5896
Número: 720
Números cuya cantidad de dígitos es múltiplo de 3: 829-102834-
Números que contienen el 0: 102834-4307-1602357-
```

**40.** Escribe un programa que permita al usuario ingresar títulos de libros por teclado, finalizando el ingreso al leerse el string “*” (asterisco). Cada vez que el usuario ingrese un string de longitud 1 que contenga sólo una barra “/” se considera que termina una línea. Por cada línea completa, informar cuántos dígitos numéricos (del 0 al 9) aparecieron en total (en todos los títulos de libros que componen en esa línea). Finalmente, informar cuántas líneas completas se ingresaron.
 
>Ejemplo de ejecución:
```shell 

Cadena: Don Quijote de La Mancha
Cadena: Los 3 mosqueteros
Cadena: Historia de 2 ciudades
Cadena: /
Aparecen 2 dígitos en la línea
Cadena: 20000 leguas de viaje submarino
Cadena: El señor de los anillos
Cadena: Alicia en el país de las maravillas
Cadena: 1984
Cadena: El hobbit
Cadena: /
Aparecen 9 dígitos en la línea
Cadena: Divina comedia
Cadena: Drácula
Cadena: /
Aparecen 0 dígitos en la línea
Cadena: 20 años después
Cadena: Los viajes de Gulliver
Cadena: *
Se leyeron 3 líneas completas
```
 
 
## 1.3. Funciones  

**41.** Escribe una función llamada esPar que reciba como parámetro un número y retorne True si el número es par ó False si es impar. Utilizar esta función en un programa que solicite al usuario el ingreso de 10 números y que luego muestre, por separado, la suma de todos los pares y la suma de todos los impares.

 >Ejemplo de ejecución:
```shell
Número: 620
Número: _12993
Número: 230
Número: 7
Número: 18
Número: 9234
Número: 38
Número: 567
Número: 8146
Número: 32
Suma de los pares: 18318
Suma de los impares: 13567
```

**42** Escribe una función llamada sumatoriaDigitos que reciba como parámetro un número y retorne la suma de todos sus dígitos, reutilizando la estrategia utilizada en el ejercicio 36. Finalmente, escribir un algoritmo que solicite al usuario ingresar varios números hasta que ingrese el número 100, con el cual cortará la repetición. Por cada número, mostrar la suma de sus dígitos, para lo cual se llamará a la función sumatoriaDigitos.
 
>Ejemplo de ejecución:
```shell
Escribe un número: 7124
Suma de los dígitos: 14
Escribe un número: 20
Suma de los dígitos: 2
Escribe un número: 916
Suma de los dígitos: 16
Escribe un número: 100
```

**43.** Escribe un programa que permita al usuario ingresar números enteros. La repetición terminará cuando el usuario ingrese un número para el cual la suma de sus dígitos sea mayor que 1000 ó múltiplo de 5. Finalmente, mostrar cuántos números impares ingresó el usuario antes de cortar la repetición. Reutilizar las funciones esPar y sumatoriaDigitos implementadas en los ejercicios anteriores.
>Ejemplo de ejecución:
```shell
Escribe un número: 16
Escribe un número: 922
Escribe un número: 1513
Escribe un número: 481
Escribe un número: 90
Cantidad de impares: 2
```

**44.** Escribe una función que reciba un string y retorne True si es un palíndromo (esto es, si se lee igual de izquierda a derecha o de derecha a izquierda), False en caso contrario. Utilizar esta función en un programa que permita al usuario ingresar palabras hasta que ingrese la palabra “fin” (suponer que todas las palabras son en minúsculas o todas en mayúsculas, de forma consistente). Al finalizar, mostrar la cantidad de palíndromos ingresados.
 
**45**. Escribe un programa que permita al usuario ingresar números enteros hasta que ingrese uno cuyo dígito inicial sea el 9 (el cual no se procesará). Una vez terminada la repetición, mostrar cuántos de los números que el usuario ingresó tienen sólo dos divisores (para esto es posible reutilizar parte de la estrategia elaborada en el ejercicio 25).

# 2. Referencias

[PatriciaEMiguel](http://patriciaemiguel.com/ejercicios/python/2019/02/24/ejercicios-principiantes-python.html)

[Pythondiario](https://pythondiario.com/ejercicios-de-programacion-python)