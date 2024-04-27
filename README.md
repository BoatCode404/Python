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


