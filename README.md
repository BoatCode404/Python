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
