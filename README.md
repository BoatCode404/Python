# AprendiendoPython
<div align="center">
 
![JjVlFLY](https://github.com/BoatCode404/AprendiendoPython/assets/166348131/35d01f2d-270b-4015-8887-d87cc5303f79)

</div>

 #### Este Espacio lo usaremos para agregar funciones , codigos , trabajos , algoritmos que vayamos aprendiendo tanto en clase como en casa
![BoatCode404](https://github.com/BoatCode404/AprendiendoPython/assets/166348131/a52d78eb-8861-4774-92a6-ca231b6feedc)
<!--
#Comience creando un archivo nuevo o cargando un archivo existente . Recomendamos que cada repositorio incluya README , LICENSE y .gitignore .
-->

### Operadores aritméticos:
- Suma(+): a + b
- Resta(-): a - b
- Multiplicación(*): a * b
- División(/): a / b
- Módulo(%): a % b
- División de piso(//): a // b
- Exponenciación(**): a ** b

## Ejemplo de operadores ##
```py
## Ejemplo de operadores ##
print("Esto es una suma ",5+3)
print("Esto es una resta ",5-3)
print("Esto es una division ",5/3)
print("Esto es una multiplicacion ",5*3)
print("Esto es una exponensiacion ",5**3)

#se usa para generar una division con un resultado entero y no decimal #
print("Esto es una division al piso ",5//3)

# Asi se suman dos cadenas de texto #
print("Yo soy" + "julian")

# Asi se suma una cadena de texto y un nuero convertido en cadena de texto con str #
print("julian " + str(5) )

myFloat=2.5*2
print("hola" * int(myFloat))

## Ejemplo de operadores comparativos ##
print(3 > 1)
print(3 < 1)
print(3 >= 1)
print(3 <= 1)
print(3 != 1)
```

# Variables​
### En programación, las variables se utilizan para almacenar valores de datos. Cada variable tiene un nombre y contiene un valor. 📦
### El nombre de la variable puede constar de letras, números y el _carácter de subrayado.
### Todos estos son nombres y valores de variables válidos:
```py
name = 'Erlich Bachman'
user_id = 16180339887
progress = 0.75
exp = 60
verified = True
```
#### El =signo igual significa asignación:
 - Estamos asignando el valor de cadena 'Erlich Bachman'a la variable name.
 - Estamos asignando el valor numérico 16180339887a la variable user_id.
 - Estamos asignando el valor numérico 0.75a la variable progress.
 - Estamos asignando el valor numérico 60a la variable exp.
 - Estamos asignando el valor de verdad Truea la variable verified.
 - También podemos cambiar el valor de una variable o imprimirlo:
```py
   xp = 70
xp = 80

print(xp)    # Output: 80
```
- Aquí, estamos asignando el valor numérico 70a la variable xp. Luego, estamos reasignando el valor numérico 80a la misma variable. E imprimirlo.



# Obtén un consejo  
![MindBlownBrookeLynnHytesGIF](https://github.com/BoatCode404/AprendiendoPython/assets/166348131/2f273207-7669-41f6-bed8-276f768d0e8d)

### Además, la raíz cuadrada de algo es lo mismo que una potencia elevada a 0,5. Entonces puedes calcular la raíz cuadrada de algo usando el operador exponente **:
![image](https://github.com/BoatCode404/AprendiendoPython/assets/166348131/a55a6125-b2b5-4b4b-acf2-53a852dc7658)

# lanzamiento de moneda
```p
import random
num=random.randint(0,1)
if num>0.5:
    print('cara')
else:
    print('sello')
````
# Objetos y clases terminos
Las clases y los objetos son dos de los conceptos fundamentales de la programación orientada a objetos.

Una "clase" en Python es como un plano para crear un objeto. Puedes considerarlo como una especie de plantilla para crear algo. Por ejemplo, podrías tener una clase "Coche", que tiene diferentes propiedades como la marca, el modelo, el color, etc., y tiene ciertos comportamientos como arrancar, acelerar, frenar, etc.

Por otro lado, un "objeto" es una instancia de una clase. Es como un coche particular que ha sido creado usando el plano del coche. Puedes tener muchos objetos de la misma clase, al igual que puedes tener muchos coches de la misma marca y modelo.

Aquí hay un pequeño ejemplo del código de Python para ilustrarlo


```py
class Coche:  # Esto es una clase
    def __init__(self, marca, modelo, color):
        self.marca = marca
        self.modelo = modelo
        self.color = color

    def arrancar(self):
        print("El coche ha arrancado")
````

# Ahora, vamos a crear un objeto de la clase Coche:
```py
mi_coche = Coche("Toyota", "Corolla", "Rojo")
# Y ahora, podemos hacer cosas con el objeto:
print(mi_coche.marca)  # Imprime "Toyota"
mi_coche.arrancar()  
# Imprime "El coche ha arrancado"
````
Espero que esto te ayude a entender el concepto. Si tienes más preguntas, ¡no dudes en preguntar! Ten en cuenta que aprender a programar es como aprender un nuevo idioma. Al principio puede parecer desalentador, pero con el tiempo y la práctica, se vuelve más fácil. ¡Sigue adelante!

no me queda claro que es un objeto

¡No hay problema, a veces los conceptos toman un tiempo para similar! Imagina que un objeto en la programación es como un objeto en el mundo real.

Por ejemplo, si considera un coche. Un coche es un objeto. Tiene propiedades específicas como color, modelo, marca y comportamientos como arrancar, acelerar y frenar. En programación, creamos una representación digital de ese coche, es decir, un "objeto" en el código que tiene las mismas propiedades (color, marca y modelo en este caso) y comportamientos (arrancar, acelerar, frenar).

Entonces, en términos de programación, crearíamos una "clase" Coche que defina todas las propiedades y comportamientos que un coche puede tener, y luego creamos "objetos" específicos de esa clase Coche.

Por ejemplo:
```py
mi_coche = Coche("Toyota", "Corolla", "Rojo")
````
En esta línea, mi_cochees ahora un objeto de la clase Coche. Tiene un color, una marca y un modelo específico. Y también puedo hacer que "arranque" o "acelere".

Los objetos son la forma que usan los programadores para representar elementos del mundo real dentro del código, lo que nos permite interactuar con ellos de manera programática.



![image](https://github.com/BoatCode404/AprendiendoPython/assets/166348131/b8b53266-6b67-452c-97d4-1f3c46c73389)


# Asi se agregan nuevos valores a una clave en el diccionario de datos de nuestro codigo 
```py
nuevo_nombre = "Neville Longbottom"
casas["Gryffindor"]["jugadores"][0] = nuevo_nombre
````

# Bucle While
El primer tipo de bucle que vamos a aprender es el whilebucle. Puedes pensar en el whilecircuito como una rotonda.

¡Cada vuelta es una iteración! Un automóvil repetirá una y otra vez hasta que ya no pueda hacerlo.
```py
print('BANK OF CODÉDEX')

pin = int(input('Enter your PIN: '))

while pin != 1234:
  pin = int(input('Incorrect PIN. Enter your PIN again: '))

if pin == 1234:
  print('PIN accepted!')
````
# rango() bucle for con funcion de rango 
Para recorrer un conjunto de código un número específico de veces, podemos usar un forbucle y la range()función.
```py
for i in range(6):
  print(i)
````
La range()función devuelve una secuencia de números. De forma predeterminada, la secuencia comienza en 0 y aumenta en 1, terminando en un número específico.


# En Python, las listas ([]) y los diccionarios ({}) son dos tipos de estructuras de datos diferentes con propósitos y características distintas:

#### Listas ([]):

Una lista es una colección ordenada y mutable de elementos.
Los elementos de una lista se almacenan en orden y se accede a ellos mediante índices enteros.
Pueden contener elementos de diferentes tipos, como números, cadenas de texto, booleanos, otras listas e incluso objetos más complejos.
Las listas se crean utilizando corchetes [] y los elementos se separan por comas.
Se pueden modificar (agregar, eliminar, cambiar) los elementos de una lista después de que se ha creado.
Ejemplo:
```py
mi_lista = [1, 2, 'hola', True]
````
#### Diccionarios ({}):

Un diccionario es una colección no ordenada y mutable de pares clave-valor.

Los elementos de un diccionario se almacenan como pares de clave-valor, donde cada clave está asociada a un valor específico.
Se accede a los valores de un diccionario mediante sus claves en lugar de índices enteros.
Los diccionarios se crean utilizando llaves {} y se especifican los pares clave-valor separados por comas y con los dos puntos : entre la clave y el valor.
Los diccionarios son útiles cuando necesitas asociar valores con claves específicas para buscarlos rápidamente.
Ejemplo:
```py
python
Copy code
mi_diccionario = {'nombre': 'Juan', 'edad': 30, 'ciudad': 'Madrid'}
````
En resumen, la principal diferencia entre listas y diccionarios radica en cómo se accede a sus elementos y cómo se almacenan los datos. Las listas son colecciones ordenadas de elementos accesibles mediante índices, mientras que los diccionarios son colecciones no ordenadas de pares clave-valor accesibles mediante las claves.



# Tuplas (()):

Una tupla es una colección inmutable y ordenada de elementos.
Se crean utilizando paréntesis () y los elementos se separan por comas.
A diferencia de las listas, las tuplas no se pueden modificar después de su creación, lo que significa que no se pueden agregar, eliminar o cambiar elementos.
Las tuplas son útiles para representar datos que no deben cambiar, como coordenadas, fechas, etc.
Ejemplo:

```py
mi_tupla = (1, 2, 'hola', True)
````
# Conjuntos ({} o set()):

Un conjunto es una colección no ordenada y mutable de elementos únicos.
Se crean utilizando llaves {} o la función set() y los elementos se separan por comas.
Los conjuntos eliminan automáticamente los elementos duplicados y no admiten elementos duplicados.
Los conjuntos son útiles para realizar operaciones como unión, intersección y diferencia entre conjuntos.
Ejemplo:
```py
mi_conjunto = {1, 2, 3, 4, 5}
````
# Cadenas de texto (str):

Una cadena de texto es una secuencia inmutable de caracteres.
Se crean utilizando comillas simples '' o dobles "".
Las cadenas de texto son muy utilizadas para representar texto y se pueden manipular de varias formas, como concatenación, indexación, división, etc.
Ejemplo:
```py
mi_cadena = 'Hola, mundo!'
````
Aprendamos una nueva herramienta que es muy similar a la concatenación de cadenas, antes de continuar con las instrucciones.
La interpolación de cadenas es un proceso de sustitución de valores de variables en marcadores de posición en una cadena.
Por ejemplo, si tiene una plantilla para saludar a una persona en un correo electrónico como 'Hi {name}, nice to meet you!', le gustaría reemplazar el marcador de posición {name}con un nombre real. Esta es la interpolación de cadenas.
El programa anterior se puede recrear usando interpolación de cadenas usando el {}signo:

\# Interpolación de cadenas

  

para i en el rango(5):

 print(f'El cuadrado de {i} es {i\*i}')

Observe el fprefijo antes de las comillas.

Casi correcto. En el caso de la función range(start, stop, step):

• El primer parámetro (start) es el valor inicial de la secuencia.

• El segundo parámetro (stop) es el valor final de la secuencia. El rango finaliza justo antes de este valor.

• El tercer parámetro (paso) es el tamaño del paso o incremento entre los valores sucesivos de la secuencia.

Entonces, para tu pregunta:

• El 0 no está presente en este caso. La secuencia comienza desde 99, que es el primer valor en este rango.

• Sí, puedes cambiar -1 a otro número, como 2, para incrementar la secuencia en pasos de 2 en 2. Por ejemplo, range(99, 0, 2) generará una secuencia que comienza en 99, termina justo antes de 0 y se disminuye de 2 en 2.

para i en el rango(99,0,-1):

 print(f"{i} botellas de cerveza en la pared, {i} botellas de cerveza. Toma uno abajo, pasa a tu alrededor, {i} botellas de cerveza en la pared...")

  

  

El whilebucle se repite una y otra vez mientras la condición sea verdadera:

mientras café < 1:

 imprimir('cansado')

  

El forbucle y la range()función para iterar un cierto número de veces:

para i en el rango(10):

 imprimir(yo)

  

1\. Se utiliza letra.lower() para convertir la letra a minúscula antes de compararla, de esta manera se consideran tanto las mayúsculas como las minúsculas. Letra es la variable

  

  

La función range() en Python crea un rango de números enteros, pero no puede manejar directamente cadenas de texto. Por eso, Python te está desarrollando un error TypeError porque estás intentando utilizar un objeto de tipo str donde se esperaba un número entero.

  

  

Entiendo, intentaré explicarlo de manera más clara.

  

En Python, la función range() crea una secuencia de números. Tiene tres parámetros:

  

El primer parámetro es el inicio de la secuencia.

El segundo parámetro es el final de la secuencia (no inclusivo).

El tercer parámetro es el paso, es decir, la diferencia entre cada número en la secuencia.

Ahora, para entender la línea for i in range(len(palabra) - 1, -1, -1): usando el ejemplo de la palabra "Python":

  

len(palabra) es 6, ya que "Python" tiene 6 letras.

len(palabra) - 1 es 5, porque queremos el índice del último carácter, pero los índices en Python comienzan desde 0.

\-1 es el final de la secuencia, pero no se incluye. Por lo tanto, la secuencia de números irá desde 5 hasta 0 (es decir, los índices del último al primer carácter).

\-1 es el paso, lo que significa que iremos hacia atrás de uno en uno.

Entonces, for i in range(len(palabra) - 1, -1, -1): genera una secuencia de números que representa los índices de los caracteres de "Python" en orden inverso, de 5 a 0. Es decir, 5 , 4, 3, 2, 1, 0. Esto permite recorrer la palabra de atrás hacia adelante.

Sí, exactamente. Cuando usas meses\[num\], accediendo al valor asociado a la clave num en el diccionario meses. En este caso, num es la clave que el usuario ingresó y meses\[num\] te dará el nombre del mes correspondiente a esa clave.




# 10. Moneda

## ¡Felicitaciones!

¡Guau! ¡Aprendiste variables en Python! 🙌

Aquí hay un resumen de todo lo que aprendimos en este capítulo:

- Tipos de datos: `int`, `float`, `str`, `bool`.
- Operadores aritméticos: `+`, `-`, `*`, `/`.
- El operador `%` encuentra el resto.
- La `**` exponenciación encuentra el exponente.
- La función `input()` se utiliza para obtener información del usuario.
- La función `int()` convierte un valor en un número entero.


# ¡Dios mío! 😱

Debido a que el promedio de la clase fue muy bajo en el examen, ¡el maestro decidió aplicar una curva a las calificaciones! 😭

---

## Programa `grades.py`

```python
# Verifica si una calificación está por encima o por debajo de 55.

# Asigna un valor a la calificación
grade = 75

# Comprueba si la calificación es mayor o igual a 55
if grade >= 55:
    print("¡Aprobaste!")
else:
    print("¡Fallaste!")
``````

# 13. Niveles de pH

## Operadores relacionales

Muchas veces dentro de las condiciones, estamos comparando dos valores. Para hacerlo, necesitamos usar un tipo diferente de operadores llamados operadores relacionales que comparan valores:

- `==` igual a
- `!=` no igual a
- `>` más grande que
- `<` menos que
- `>=` Mayor qué o igual a
- `<=` Menos que o igual a

Además, podemos usar la declaración `elif` (abreviatura de "else if") para proporcionar condiciones adicionales para verificar. A veces dos simplemente no son suficientes.

```python
if grade > 90:
  print('A')
elif grade > 80:
  print('B')
elif grade > 70:
  print('C')
elif grade > 60:
  print('D')
else:
  print('F')
``````

# Operadores lógicos

Una cosa más que deberíamos aprender son los operadores lógicos.

Los operadores lógicos, también conocidos como operadores booleanos, combinan y evalúan dos condiciones. Son los operadores `and`, `or` y `not`:

- `and` devuelve `True` si ambas condiciones son `True` y devuelve `False` en caso contrario.
- `or` devuelve `True` si al menos una de las condiciones es `True` y `False` en caso contrario.
- `not` devuelve `True` si la condición es `False` y viceversa.

Aquí hay unos ejemplos:

```python
if hunger > 4 and anger > 1:
  print('¡Hangry!')

if coffee > 0 or bubble_tea > 0:
  print('😊')

if not tired:
  print('¡Es hora de codificar!')
````````

#### Quizás te preguntes: `and` y `or` son tremendamente similares, ¿cómo recuerdo las diferencias entre los dos? Analicemos esto en forma de tabla:

| A      | B      | A y B  | A o B  |
|--------|--------|--------|--------|
| False  | False  | False  | False  |
| False  | True   | False  | True   |
| True   | False  | False  | True   |
| True   | True   | True   | True   |

# ¡Felicitaciones!

Aquí hay un resumen de todo lo que aprendimos hasta ahora:

- El flujo de control es el orden en que se ejecuta el código del programa.
- La declaración `if` prueba la verdad de una condición y ejecuta el código si es `True`.
- La cláusula `elif` se puede agregar entre `if` y `else`.
- `else` ejecuta el código si ninguna de las condiciones anteriores es `True`.
- Los operadores relacionales se utilizan para comparar dos valores: `==`, `!=`, `>`, `>=`, `<`, `<=`.
- Los operadores lógicos se utilizan para combinar dos o más condiciones: `and`, `or`, `not`.

Aquí hay una declaración `if` en acción por si acaso:

```python
if review >= 4.5:
  print('Extraordinary')
elif review >= 4:
  print('Excellent')
elif review >= 3:
  print('Good')
else:
  print('Eh')
``````

# Lista de compras

\### Listas

¡Bienvenido a un capítulo completamente nuevo, donde aprenderemos sobre una forma sencilla de almacenar una gran cantidad de valores de datos! 📦 = ⚽️🏀⚾️🥎🏐🏈

  

Supongamos que queremos crear un programa que almacene nuestras calificaciones escolares para tareas y exámenes, necesitaríamos crear un montón de variables como estas:

  

\`\`\`py

\# Almacenar calificaciones en una clase

  

hw\_grado1 = 98

hw\_grado2 = 87

hw\_grado3 = 92

hw\_grado4 = 96

  

cuestionario\_grado1 = 9

cuestionario\_grado2 = 6

cuestionario\_grado3 = 8

\`\`\`\`

  

Crear un montón de variables de esta manera es tedioso y propenso a errores. ¿Te imaginas cómo sería con más de 1000 variables?

  

Las listas se utilizan para almacenar varios elementos en una sola variable.

  

Podemos reescribir el código anterior para:

\`\`\`\`py

\# Almacenar calificaciones en una clase

  

hw\_grados = \[98, 87, 92, 96\]

calificaciones\_prueba = \[9, 6, 8\]

\`\`\`\`

La sintaxis de una lista es la siguiente:

\`\`\`py

nombre\_lista = \[elemento1, elemento2, elemento3, elemento4\]

\`\`\`\`

Las listas se crean utilizando corchetes '\[y \]'. Y los elementos están separados por comas.

  

\# Ejemplos

Datos que podrían almacenarse en una lista:

  

\- Temperaturas en la última semana.

\- Nivel de pH de la planta de oficinas en la última hora.

\-Las consultas recientes que un usuario escribió en una barra de búsqueda.

\`\`\`py

temperatura = \[86, 80, 82, 87, 79, 80, 81, 82\]

ph = \[7,2, 7,1, 7,0, 7,0, 7,2, 7,1\]

now\_playing = \['Barbie', 'Oppenheimer', 'Háblame', 'Escarabajo Azul'\]

\`\`\`\`

Más datos sobre las listas:

  

\- Los elementos de la lista permiten valores duplicados.

\- Las listas pueden tener valores con diferentes tipos de datos.

\- No hay límite para la cantidad de datos que puede contener una lista.

\- Instrucciones


## Índice

Los elementos de la lista se pueden cambiar, lo que significa que podemos actualizar elementos individuales dentro de una lista.

Pero antes de hacer eso, ¿cómo podemos acceder a un elemento individual dentro de una lista? Bueno, ¡aquí es donde entra en juego el índice!

Un índice es la posición de un elemento en una lista.

Python tiene un índice de 0, lo que significa que los índices comienzan en 0:

```python
vowels = ['a', 'e', 'i', 'o', 'u']
# Index:   0    1    2    3    4
El elemento en el índice 0 es 'a'.
El artículo en el índice 1 es 'e'.
El artículo en el índice 2 es 'i'.
El artículo en el índice 3 es 'o'.
El artículo en el índice 4 es 'u'.
````
Para generar cada uno de los elementos, podemos usar la nombre[indice] sintaxis:

```py
print(vowels[0])     # Salida: a
print(vowels[1])     # Salida: e
print(vowels[2])     # Salida: i
print(vowels[3])     # Salida: o
print(vowels[4])     # Salida: u
``````
# Índice negativo
Otra cosa a tener en cuenta sobre el índice es que puede ser positivo o negativo.

Si el índice es negativo, comienza desde -1 (que es el último elemento de una lista) y retrocede desde allí.
```py
vowels = ['a', 'e', 'i', 'o', 'u']
# Index:   0    1    2    3    4
# Index:  -5   -4   -3   -2   -1
El elemento en el índice -5 es 'a'.
El elemento en el índice -4 es 'e'.
El elemento en el índice -3 es 'i'.
El elemento en el índice -2 es 'o'.
El elemento en el índice -1 es 'u'.
``````
# Rebanar
¿Hay alguna manera de obtener más de un artículo individual? ¡Sí! Se llama rebanar.

Cortar es donde podemos acceder a ciertas partes de una secuencia.

En lugar de acceder a un elemento utilizando un único índice como nombre[indice], podemos obtener varios elementos especificando dónde comenzar y dónde terminar el rango como nombre[inicio: fin].

Por ejemplo:

```py
vowels = ['a', 'e', 'i', 'o', 'u']

print(vowels[0:3])
print(vowels[1:3])

# Output:
# ['a', 'e', 'i']
# ['e', 'i']
````
Comienza desde el inicio índice (inclusivo) y termina antes del fin índice (no incluido). Entonces, en el ejemplo anterior, `print(vowels[1:3])` solo se devolvieron elementos en los índices 1 y 2, y no se incluyó el índice 3.

# Error de índice

Hay un error común en Python cuando se trata de secuencias llamado IndexError. Esto es lo que sucede cuando el índice está fuera del rango de una lista.

Por ejemplo, cuando intentamos hacer `vowels[5]`, obtendremos algo como:

```py
Traceback (most recent call last):
    print(vowels[5])
IndexError: list index out of range
````
¡Así que asegúrate de tener cuidado con eso!




# Errores en Python
En este punto del viaje, es posible que haya encontrado uno o dos errores al ejecutar el código. Aquí hay algunos errores comunes de Python:

- SyntaxError: esto ocurre cuando hay código Python no válido.
- NameError: esto ocurre cuando intentas utilizar una variable sin declararla primero.
- TypeError: esto ocurre cuando el tipo de datos que estás usando no se adapta a lo que estás intentando hacer.
- Durante tu aventura de codificación, estás destinado a encontrar innumerables pequeños y molestos errores rojos. Pero lo que hace grande a un programador no es evitar los errores, sino saber afrontarlos y resolverlos. 💪

### ¡Exploremos estos a continuación!

- Error de sintaxis
Uno de los errores más comunes es el SyntaxError, que ocurre cuando intentas ejecutar código que no es Python válido, como una palabra clave mal escrita, dos puntos faltantes :o un paréntesis de cierre faltante.

Por ejemplo:
````py
print(Hello, World!

# SyntaxError: invalid syntax
``````
El fragmento anterior generará un mensaje SyntaxErrorcuando se ejecute porque la print()función requiere un paréntesis de cierre. Además, '¡Hola mundo!' debe estar entre comillas.

El mensaje de error completo podría verse así:
````
  File "main.py", line 1
    print(Hello, World!
                      ^
SyntaxError: invalid syntax
````
Describe File "main.py", line 1el nombre del archivo y el número de línea.
La pequeña flecha ^señala donde se detectó el error.

Nota: La flecha ^puede ser engañosa a veces porque es ahí donde el programa "piensa" que está el error; ¡Hay ocasiones en las que los errores ocurren antes de donde apunta!

### Error de nombre
Otro error con el que te encontrarás a menudo es el NameError, que ocurre cuando intentas hacer referencia a una variable que aún no se ha creado; podría deberse a que escribiste mal el nombre de una variable o te olvidaste de definirla.

Por ejemplo:
```py
print(greetings)

# NameError: name 'greetings' is not defined
````
El fragmento anterior arroja un NameError porque no habíamos definido una greetingsvariable. Podemos solucionar esto definiendo la variable de antemano:
solucion:
```py
greetings = 'Howdy 🤠'
print(greetings)

Output: Howdy 🤠
````
### Error de tecleado
Otro error común que veremos es el TypeError. Cuando trabaje con variables de varios tipos de datos (por ejemplo, números, cadenas y valores booleanos), probablemente encontrará este error.

Por ejemplo:
````
message = 'The air quality is '
print(message + 28)

# TypeError: can only concatenate str (not "int") to str
````
La messagevariable es un tipo de datos de cadena. Si intentamos agregarle un número entero 28, TypeErrorse arrojará a. Esto se puede solucionar con algo como la función incorporada str()o encerrando el número entre comillas:
solucion
```py
message = 'The air quality is '
print(message + str(28))

# Output: The air quality is 28
````
¡Eso es todo por ahora! Si te encuentras con un error que no está en la lista, asegúrate de visitar la documentación oficial de Python para ver el resto.

Y no olvide pegar también su mensaje de error en una búsqueda de Google.


# Declaraciones If anidadas
Sintaxis
A medida que nuestro programa se vuelve más largo y complejo, también lo hace la toma de decisiones de nuestro código. Es posible que ya se haya encontrado con situaciones en las que desee comprobar si hay otra condición después de que una condición sea verdadera.

¿Sabes qué más podemos hacer con las declaraciones if// ?elifelse

¡Podemos anidarlos uno dentro del otro! 🪹

Una declaración if anidada es una ifdeclaración dentro de otra ifdeclaración.

Supongamos que tenemos una declaración if/ simple else:

if age >= 18:
  print('You are old enough to apply for a loan.')
else:
  print('You are too young to apply for a loan.')

Agreguemos otra declaración if/ elseanidada dentro de la declaración externa if:

if age >= 18:
  if income >= 20000:
    print('You are eligible for a loan.')
  else:
    print('Your income is too low to be eligible for a loan.')
else:
  print('You are too young to apply for a loan.')

En Python, la sangría es la única forma de determinar el nivel de anidamiento. Debido a que las líneas 2 a 5 tienen más sangría, están dentro de la ifdeclaración exterior.

Aquí está el flujo de control del programa:

declaraciones if anidadas

Nota: Pero tenga cuidado. Anidar estas declaraciones demasiado profundamente (más allá de 2 o 3 niveles) generalmente no es una buena idea, ya que esto podría hacer que su programa sea difícil de leer.

# Ejemplo
El siguiente ejemplo ilustra cómo las declaraciones de flujo de control anidadas pueden afectar la salida de un programa:

weather = 'Sunny'
humidity = 35

if weather == 'Sunny':
  if humidity < 60:
    print('Let’s go to the beach! 🏖️')
  else:
    print('Hmmm, it’s a little humid for a beach day.')
else:
  print('It’s not sunny today... let’s try for another day.')

Esto imprimirá lo siguiente:

Let's go to the beach! 🏖️

Si humidityes 65, entonces el resultado sería:

Hmmm, it's a little humid for a beach day.

¡Ahora puedes agregar capas de toma de decisiones a tus programas!



# Bucles anidados
De manera similar a como puedes anidar declaraciones if// , elif¡ elsetambién puedes anidar bucles!

Un bucle anidado es un bucle que tiene otro bucle dentro. Por ejemplo:

for i in range(1, 6):
  for j in range(1, 6):
    print(i * j)

Hay un forbucle exterior con un forbucle interior anidado. Para recorrer una iteración del bucle externo, tenemos que recorrer todo el bucle anidado.

En Python podemos hacer lo mismo con whilelos bucles anidados:

i = 0
while i < 6:
  j = 0
  while j < 6:
    print(i * j)
    j = j + 1
  i = i + 1

Fuera de cada uno while, inicializamos variables de contador simples iy j. Con cada iteración del whilebucle exterior, recorremos 6 iteraciones del whilebucle anidado. Podemos salir de estos bucles actualizando las variables del contador iy jdespués de cada iteración.

# Ejemplo
¡También puedes usar una combinación de tipos de bucles para anidar! Mira el siguiente ejemplo:

import random

lucky_number = random.randint(1, 10)
not_found = True

while not_found:
  for i in range(1, 10):
    if i == lucky_number:
      not_found = False
      break
    else:
      print(i)
print(f"Yay I got my lucky number {lucky_number}! 🍀")

El bucle externo whilesiempre que la not_foundvariable booleana sea True.

Para el forbucle interno, estamos iterando de 1 a 10. Nos detenemos temprano cuando la ivariable es igual a lucky_number.

Para salir del forbucle, utilizamos la breakpalabra clave. Para salir del whilebucle exterior, reasignamos Falsea la notFoundvariable.****



-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Listas
22. Lista de compras
# Listas
¡Bienvenido a un capítulo completamente nuevo, donde aprenderemos sobre una forma sencilla de almacenar una gran cantidad de valores de datos! 📦 = ⚽️🏀⚾️🥎🏐🏈

Supongamos que queremos crear un programa que almacene nuestras calificaciones escolares para tareas y exámenes, necesitaríamos crear un montón de variables como estas:

# Storing grades in a class

hw_grade1 = 98
hw_grade2 = 87
hw_grade3 = 92
hw_grade4 = 96

quiz_grade1 = 9
quiz_grade2 = 6
quiz_grade3 = 8

Crear un montón de variables de esta manera es tedioso y propenso a errores. ¿Te imaginas cómo sería con más de 1000 variables?

Las listas se utilizan para almacenar varios elementos en una sola variable.

Podemos reescribir el código anterior para:

# Storing grades in a class

hw_grades = [98, 87, 92, 96]
quiz_grades = [9, 6, 8]

La sintaxis de una lista es la siguiente:

list_name = [item1, item2, item3, item4]

Las listas se crean utilizando corchetes [y ]. Y los elementos están separados por ,comas.

# Ejemplos
Datos que podrían almacenarse en una lista:

Temperaturas en la última semana.
Nivel de pH de la planta de oficinas en la última hora.
Las consultas recientes que un usuario escribió en una barra de búsqueda.
temp = [86, 80, 82, 87, 79, 80, 81, 82]
ph = [7.2, 7.1, 7.0, 7.0, 7.2, 7.1]
now_playing = ['Barbie', 'Oppenheimer', 'Talk to Me', 'Blue Beetle']

Más datos sobre las listas:

Los elementos de la lista permiten valores duplicados.
Las listas pueden tener valores con diferentes tipos de datos.
No hay límite para la cantidad de datos que puede contener una lista.
Instrucciones

# índice
Los elementos de la lista se pueden cambiar, lo que significa que podemos actualizar elementos individuales dentro de una lista.

Pero antes de hacer eso, ¿cómo podemos acceder a un elemento individual dentro de una lista? Bueno, ¡aquí es donde entra en juego el índice!

Un índice es la posición de un elemento en una lista.

Python tiene un índice de 0, lo que significa que los índices comienzan en 0:

vowels = ['a', 'e', 'i', 'o', 'u']
# Index:   0    1    2    3    4

El elemento en el índice 0 es 'a'.
El artículo en el índice 1 es 'e'.
El artículo en el índice 2 es 'i'.
El artículo en el índice 3 es 'o'.
El artículo en el índice 4 es 'u'.
Para generar cada uno de los elementos, podemos usar la name[index]sintaxis:

print(vowels[0])     # Output: a
print(vowels[1])     # Output: e
print(vowels[2])     # Output: i
print(vowels[3])     # Output: o
print(vowels[4])     # Output: u

# Índice negativo
Otra cosa a tener en cuenta sobre el índice es que puede ser positivo o negativo.

Si el índice es negativo, comienza desde -1 (que es el último elemento de una lista) y retrocede desde allí.

vowels = ['a', 'e', 'i', 'o', 'u']
# Index:   0    1    2    3    4
# Index:  -5   -4   -3   -2   -1

El elemento en el índice -5 es 'a'.
El elemento en el índice -4 es 'e'.
El elemento en el índice -3 es 'i'.
El elemento en el índice -2 es 'o'.
El elemento en el índice -1 es 'u'.
# Rebanar
¿Hay alguna manera de obtener más de un artículo individual? ¡Sí! Se llama rebanar.

Cortar es donde podemos acceder a ciertas partes de una secuencia.

En lugar de acceder a un elemento utilizando un único índice como name[index], podemos obtener varios elementos especificando dónde comenzar y dónde terminar el rango como name[start : end].

Por ejemplo:

vowels = ['a', 'e', 'i', 'o', 'u']

print(vowels[0 : 3])
print(vowels[1 : 3])

# Output:
# ['a', 'e', 'i']
# ['e', 'i']

Comienza desde el startíndice (inclusivo) y termina antes del endíndice (no incluido). Entonces, en el ejemplo anterior, print(vowels[1 : 3])solo se devolvieron elementos en los índices 1 y 2, y no se incluyó el índice 3.

# Error de índice
Hay un error común en Python cuando se trata de secuencias llamado IndexError. Esto es lo que sucede cuando el índice está fuera del rango de una lista.

Por ejemplo, cuando intentamos hacer vowels[5], obtendremos algo como:

Traceback (most recent call last):
    print(vowels[5])
IndexError: list index out of range

¡Así que asegúrate de tener cuidado con eso!

# Funciones integradas
Python viene con algunas funciones integradas, incluidas algunas específicas para listas.

Aquí hay unos ejemplos:

La len()función devuelve la longitud total de una lista.
La max()función devuelve el valor máximo en una lista.
La min()función devuelve el valor mínimo en una lista.
Supongamos que tenemos dos listas que se ven así:

stock1_prices = [2.52, 2.44, 2.32, 2.41, 2.51, 2.50, 2.44]
stock2_prices = [8.36, 8.31, 8.21, 8.21, 8.25, 8.11, 8.13]

print(len(stock1_prices))      # Output: 7
print(max(stock1_prices))      # Output: 2.52
print(min(stock2_prices))      # Output: 8.11

Podemos encontrar la longitud, el mínimo y el máximo de una lista en una fracción de segundo, ¡incluso si la lista tiene más de 1000 elementos!

Para obtener más información, aquí están todas las funciones integradas de Python . Sin embargo, ¡no todas las funciones integradas están diseñadas para funcionar con listas!



Aquí tienes el texto convertido a Markdown, con una explicación detallada y ejemplos de código:

---

# Explicacion del KEY=

El parámetro `key` se utiliza para especificar una función que define el criterio de ordenamiento. Por ejemplo, si queremos ordenar una lista no solo de menor a mayor, sino también según la longitud de caracteres de cada elemento en la lista, podemos usar el parámetro `key`.

**Ordenar una lista de cadenas de texto por su longitud en lugar de alfabéticamente:**
```python
fruits = ["manzana", "plátano", "uva", "naranja", "kiwi"]
sorted_fruits = sorted(fruits, key=len)

print("Lista de frutas ordenada por longitud:")
for fruit in sorted_fruits:
    print(fruit)
```

**Ordenar una lista de números de mayor a menor basado en el valor absoluto:**
```python
numbers = [5, -3, 2, -10, 8, -1]
sorted_numbers = sorted(numbers, key=abs, reverse=True)

print("\nLista de números ordenada de mayor a menor basado en el valor absoluto:")
for number in sorted_numbers:
    print(number)
```

**Este código producirá la siguiente salida:**
```
Lista de frutas ordenada por longitud:
uva
kiwi
manzana
plátano
naranja

Lista de números ordenada de mayor a menor basado en el valor absoluto:
-10
8
5
-3
-1
2
```

---

# Métodos de lista

#### Breve Explicacion
Además de las funciones integradas, Python tiene una serie de **métodos de lista integrados** que son muy útiles.

Éstos son algunos de ellos:

- **`.append()`**: El método agrega un elemento al final de la lista.
- **`.insert()`**: El método agrega un elemento a un índice específico.
- **`.remove()`**: El método elimina un elemento de una lista según el valor.
- **`.pop()`**: El método elimina el elemento en un índice particular.

¡Usemos secuencias de ADN como ejemplo para esto! 🧬

```python
dna = ['AUG', 'AUC', 'UCG']

dna.append('UAA')     # ['AUG', 'AUC', 'UCG', 'UAA']
dna.insert(2, 'GAU')  # ['AUG', 'AUC', 'GAU', 'UCG', 'UAA']
dna.remove('AUC')     # ['AUG', 'GAU', 'UCG', 'UAA']
dna.pop(0)            # ['GAU', 'UCG', 'UAA']
```

La diferencia entre **funciones integradas** y **métodos** en una lista es que los métodos usan la sintaxis de notación de puntos en la variable de lista que creamos. Las funciones integradas se pueden llamar por sí mismas, pero los métodos siempre están adjuntos a una variable de lista desde la cual se llaman.

Otra diferencia notable es que, si bien no todas las funciones integradas están definidas para funcionar con listas, los métodos de lista solo funcionan con listas.

#### Aquí están los 11 métodos de lista para guardar en sus notas:

| Método de lista | Descripción |
| --- | --- |
| **`.append()`** | Agregar un elemento al final de la lista |
| **`.clear()`** | Eliminar todos los elementos de la lista |
| **`.copy()`** | Devolver una copia superficial de la lista |
| **`.count()`** | Devuelve el número de veces que aparece el valor en la lista |
| **`.extend()`** | Agrega otra lista a la lista actual extendiéndola |
| **`.index()`** | Devuelve el índice de un valor dentro de la lista |
| **`.insert()`** | Insertar un elemento en una posición especificada en la lista |
| **`.pop()`** | Eliminar un elemento de una posición específica en la lista |
| **`.remove()`** | Eliminar un artículo de la lista según el valor del artículo |
| **`.reverse()`** | Invierte la lista en su lugar |
| **`.sort()`** | Ordena la lista en su lugar |

##### Aca Estan Los ejemplos de cada uno de ellos y hay mas terminos
1. **`.append()`**: Agrega un elemento al final de la lista.
   ```python
   numbers = [1, 2, 3]
   numbers.append(4)
   print(numbers)  # Salida: [1, 2, 3, 4]
   ```

2. **`.clear()`**: Elimina todos los elementos de la lista.
   ```python
   numbers = [1, 2, 3]
   numbers.clear()
   print(numbers)  # Salida: []
   ```

3. **`.copy()`**: Devuelve una copia superficial de la lista.
   ```python
   numbers = [1, 2, 3]
   numbers_copy = numbers.copy()
   print(numbers_copy)  # Salida: [1, 2, 3]
   ```

4. **`.count()`**: Devuelve el número de veces que aparece un valor en la lista.
   ```python
   numbers = [1, 2, 2, 3, 3, 3]
   count = numbers.count(3)
   print(count)  # Salida: 3
   ```

5. **`.extend()`**: Agrega los elementos de una lista (o cualquier iterable) al final de la lista actual.
   ```python
   numbers = [1, 2, 3]
   more_numbers = [4, 5, 6]
   numbers.extend(more_numbers)
   print(numbers)  # Salida: [1, 2, 3, 4, 5, 6]
   ```

6. **`.index()`**: Devuelve el índice del primer elemento con el valor especificado.
   ```python
   numbers = [10, 20, 30, 40, 50]
   index = numbers.index(30)
   print(index)  # Salida: 2
   ```

7. **`.insert()`**: Inserta un elemento en la posición especificada.
   ```python
   numbers = [1, 2, 3, 4, 5]
   numbers.insert(2, 10)
   print(numbers)  # Salida: [1, 2, 10, 3, 4, 5]
   ```

8. **`.pop()`**: Elimina y devuelve el elemento en la posición dada.
   ```python
   numbers = [1, 2, 3, 4, 5]
   popped_element = numbers.pop(2)
   print(numbers)        # Salida: [1, 2, 4, 5]
   print(popped_element) # Salida: 3
   ```

9. **`.remove()`**: Elimina el primer elemento con el valor especificado.
   ```python
   numbers = [1, 2, 3, 4, 5]
   numbers.remove(3)
   print(numbers)  # Salida: [1, 2, 4, 5]
   ```

10. **`.reverse()`**: Invierte los elementos de la lista.
    ```python
    numbers = [1, 2, 3, 4, 5]
    numbers.reverse()
    print(numbers)  # Salida: [5, 4, 3, 2, 1]
    ```

11. **`.sort()`**: Ordena los elementos de la lista.
    ```python
    numbers = [3, 2, 1, 5, 4]
    numbers.sort()
    print(numbers)  # Salida: [1, 2, 3, 4, 5]
    ```

12. **`sorted()`**: Devuelve una nueva lista ordenada sin modificar la original.
    ```python
    numbers = [3, 2, 1, 5, 4]
    sorted_numbers = sorted(numbers)
    print(sorted_numbers)  # Salida: [1, 2, 3, 4, 5]
    ```

13. **`reversed()`**: Devuelve un iterador que accede a los elementos de la lista en orden inverso.
    ```python
    numbers = [1, 2, 3, 4, 5]
    reversed_numbers = list(reversed(numbers))
    print(reversed_numbers)  # Salida: [5, 4, 3, 2, 1]
    ```

14. **`max()`**: Devuelve el elemento máximo de la lista.
    ```python
    numbers = [3, 7, 2, 8, 5]
    max_number = max(numbers)
    print(max_number)  # Salida: 8
    ```

15. **`min()`**: Devuelve el elemento mínimo de la lista.
    ```python
    numbers = [3, 7, 2, 8, 5]
    min_number = min(numbers)
    print(min_number)  # Salida: 2
    ```

16. **`sum()`**: Devuelve la suma de todos los elementos de la lista.
    ```python
    numbers = [1, 2, 3, 4, 5]
    total = sum(numbers)
    print(total)  # Salida: 15
    ```

17. **`len()`**: Devuelve la longitud de la lista.
    ```python
    numbers = [1, 2, 3, 4, 5]
    length = len(numbers)
    print(length)  # Salida: 5
    ```

    # FOR en Listas y LEN

Ahora quizás te preguntes: ¿hay alguna manera de iterar sobre una lista? 🔁

**Sí**, ¡hay varias formas de iterar sobre una lista en Python! En este ejercicio, te mostraremos diferentes formas de hacerlo.

### Por Entrada
La primera forma es utilizar un bucle `for-in`. He aquí un ejemplo:

```python
snowfall = [0.3, 0.0, 0.0, 1.2, 3.9, 2.2, 0.8]

for i in snowfall:
    print(i)
```

`i` es una variable que representa un elemento dentro de la lista, cada vez que se itera el bucle. Esto significa que para cada elemento `i` de la lista `snowfall`, imprima el elemento. La salida será:

```
0.3
0.0
0.0
1.2
3.9
2.2
0.8
```

### For-In con Range() y Len()
También podemos recorrer una lista usando el índice (posición). Para hacerlo, necesitamos la función `range()` y la función `len()`.

Como recordatorio:

- La función `range()` devuelve una secuencia de números, del 0 al número especificado.
- La función `len()` devuelve la longitud de la lista.

```python
snowfall = [0.3, 0.0, 0.0, 1.2, 3.9, 2.2, 0.8]

for i in range(len(snowfall)):
    print(snowfall[i])
```

Aquí `i` es un índice. Esto significa que para cada índice desde 0 hasta la longitud de `snowfall` menos 1 (7 - 1 = 6), imprima el elemento en ese índice.

Este es un código en Python que imprime cada elemento de la lista `snowfall`. La lista `snowfall` contiene los datos de acumulación de nieve durante varios días.

El código utiliza un bucle `for` para iterar sobre cada elemento de la lista `snowfall`. La función `len(snowfall)` devuelve la longitud de la lista `snowfall`, y `range(len(snowfall))` genera una secuencia de números desde 0 hasta la longitud de la lista `snowfall` menos 1.

Por lo tanto, `for i in range(len(snowfall)):` itera sobre los índices de la lista `snowfall`, y `snowfall[i]` accede al elemento en la posición `i` de la lista `snowfall`. Finalmente, `print(snowfall[i])` imprime cada elemento de la lista `snowfall` en una línea separada.

El resultado de este código sería:

```
0.3
0.0
0.0
1.2
3.9
2.2
0.8
```
En Python, los índices de una lista comienzan desde 0. Por lo tanto, si una lista tiene `n` elementos, los índices válidos van desde 0 hasta `n-1`.

Cuando usamos `range(len(snowfall))`, `len(snowfall)` devuelve el número de elementos en la lista `snowfall`, y `range()` genera una secuencia de números desde 0 hasta `len(snowfall) - 1`, para que coincida con los índices válidos de la lista.

Por ejemplo, si `len(snowfall)` es 7, el rango será `range(7)`, que generará números desde 0 hasta 6, que son los índices válidos para una lista con 7 elementos.


# ¡Felicitaciones!

Acabas de agregar una herramienta muy útil a tu caja de herramientas de codificación: **¡listas!**

He aquí un resumen del capítulo:

- Las listas se utilizan para almacenar diferentes elementos en una sola variable.
- Un índice es la posición de un elemento en una lista. Las listas de Python están indexadas en 0.
- Slicing puede acceder a ciertas partes de una lista con `name[start:end]`.
- Python tiene funciones integradas como `len()`, `max()`, `min()`.
- Las listas tienen métodos integrados como `.append()`, `.insert()`, `.remove()`, `.pop()`.
- Podemos iterar sobre una lista usando `for-in`.

Por supuesto, puedo convertir tu texto sobre parámetros y argumentos en funciones a formato Markdown. Aquí está:

```markdown
# Parámetros y Argumentos

Hasta ahora, las funciones que hemos creado no aceptan ninguna entrada, lo que significa que hacen lo mismo cada vez que son llamadas. ¡Una función puede ser mucho más útil que eso!

## Introducción a los Parámetros

A veces, queremos que nuestras funciones realicen una tarea específica, pero la tarea varía según las diferentes entradas. Y ahí es donde entran los **parámetros**.

Los parámetros son variables que una función toma como entrada. Van dentro de los paréntesis en la definición de la función y se usan dentro de la función.

## Ejemplo de Función sin Parámetros

```python
def happy_birthday():
  print('Happy birthday to you')
  print('Happy birthday to you')
  print('Happy birthday dear friend')
  print('Happy birthday to you')

happy_birthday()
```

Esto imprime lo mismo cada vez.

## Personalizando Funciones con Parámetros

Digamos que queremos hacer la canción más personalizada. Por ejemplo, digamos el nombre de la persona en lugar de simplemente “querido amigo”, entonces podemos hacer esto:

```python
def happy_birthday(name):
  print('Happy birthday to you')
  print('Happy birthday to you')
  print('Happy birthday dear ' + name)
  print('Happy birthday to you')
```

Aquí, le dimos a la `happy_birthday()` función un `name` parámetro para que lo asuma. Entonces podemos usar la `name` variable dentro del cuerpo de la función.

## Llamando a la Función con Argumentos

Y más adelante en el programa, cuando llamamos a la `happy_birthday()` función, podemos agregar un argumento en la llamada.

```python
happy_birthday('Lillian')
```

La salida sería:

```
Happy birthday to you
Happy birthday to you
Happy birthday dear Lillian
Happy birthday to you
```

## Diferencia entre Parámetro y Argumento

Entonces, ¿cuál es la diferencia entre un parámetro y un argumento? ¿Por qué hay dos palabras para lo mismo?

- El **parámetro** es la variable que figura entre paréntesis en la definición de la función (cuando definimos la función).
- El **argumento** es el valor enviado a la función (cuando llamamos a la función).

En el ejemplo anterior, la variable `name` es el parámetro y el valor 'Lillian' es el argumento.

## Uso de Argumentos en Funciones Comunes

Por cierto, ya hemos estado usando argumentos todo el tiempo, al llamar a la `print()` función, por ejemplo. En `print('Yo!')`, el 'Yo!' es el argumento.

## Instrucciones


