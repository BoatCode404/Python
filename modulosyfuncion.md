# usamos import random y Podemos usar la .randint()función de un módulo llamado randompara generar un número aleatorio de un rango.
```py
import random
num=random.randint(0,5)
````
# Uasamos Este codigo para conocer el dato mayor de un diccionario 
```py
casa_ganadora=max(acomulador,key=acomulador.get)
````
- acomulador es la variable de nuestro diccionario en este caso

# random.choice() 
es una función en el módulo random de Python que se utiliza para elegir aleatoriamente un elemento de una secuencia, como una lista, una tupla o una cadena de texto.
```py
import random

# Lista de colores
colores = ["rojo", "azul", "verde", "amarillo"]

# Elegir un color aleatorio
color_aleatorio = random.choice(colores)

print("El color aleatorio seleccionado es:", color_aleatorio)
````

# random.shuffle 
es una función en el módulo random de Python que se utiliza para mezclar los elementos de una secuencia de manera aleatoria. Esta función modifica la secuencia en su lugar, reorganizando sus elementos de forma aleatoria.

````py
import random

# Lista de números del 1 al 10
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# Mezclar los números
random.shuffle(numeros)
print("Lista de números mezclados:", numeros)
````
