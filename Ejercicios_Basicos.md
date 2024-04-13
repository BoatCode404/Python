

# Ejercicios Basicos en Python

![image](https://github.com/BoatCode404/AprendiendoPython/assets/166348131/123a5cfa-d26c-43bf-8df9-82f591ba4dfe)

```py
''''
1.Declara tu edad como variable entera
2.Declara tu altura como una variable flotante
3.Declarar una variable que almacene un número complejo
'''''
edad=int(18)
miAltura=float(1.78)
complex=complex(3+4j)

# 4.Escriba un script que solicite al usuario que ingrese la base y la altura del triángulo y calcule el área de este triángulo (área = 0,5 x b x h).

base=float(input("Cual es la Base del triangulo: "))
altura=float(input("Cual es la Altura del triangulo: "))
area=print("la altura del triangulo es " ,0.5 * base * altura)

# 5.Escriba un script que solicite al usuario que ingrese el lado a, el lado b y el lado c del triángulo. Calcula el perímetro del triángulo (perímetro = a + b + c).

lado1=float(input("Cual es el lado 1 del triangulo: "))
lado2=float(input("Cual es el lado 2 del triangulo: "))
lado3=float(input("Cual es el lado 3 del triangulo: "))
perimetro=print("el perimetro del triangulo es: ",lado1+lado2+lado3/2)

# 6.Obtenga el largo y el ancho de un rectángulo usando el mensaje. Calcula su área (área = largo x ancho) y perímetro (perímetro = 2 x (largo + ancho))

largo=float(input("Cual es el largo del rectangulo: "))
ancho=float(input("Cual es el ancho del rectangulo: "))
areaRectangulo=print("el area del rectangulo es: ",largo*ancho)
perimetroRectangulo=print("el area del rectangulo es: ",2*(largo+ancho))

# 7.Obtenga el radio de un círculo usando el mensaje. Calcula el área (área = pi xrxr) y la circunferencia (c = 2 x pi xr) donde pi = 3,14.

pi=3.14
radio=float(input("Cual es el radio del circulo: "))
areaCirculo=print("El area del circulo es:",pi*radio*radio)
circunferencia=print("la cirfunferencia del circulo es:",2*pi*radio)

# 8.Calcula la pendiente, la intersección x y la intersección y de  y = (2x -2) importante 2 es el  metro o pendiente por que esta mas cerca de la x

m=2   #pendiente 
b=-2  # interseccion y

interseccionX= -b/m
print("pendiente es :",m)
print("la interseccion de y es:",b)
print("la interseccion de x es :",interseccionX)
````

![image](https://github.com/BoatCode404/AprendiendoPython/assets/166348131/802f948c-e5dc-400e-a606-34164034de24)
<div align="center">
  
# Convertir números romanos con Python                                                                                              
 ### Requisitos previos : Fundamentos de Python
 ### Versión : Python 3.10
 ### Tiempo de lectura : 30 minutos
 ```py
#Con estos numeros y los de la imagen podemos sumar todos los numeros romanos 
CM=900
CD=400
XC=90
XL=40
IX=9
IV=4
```
 ![image](https://github.com/BoatCode404/AprendiendoPython/assets/166348131/ab21efab-d438-4d42-9bfd-a0dbea90a58b),
</div>

# Introducción
Los números romanos se originaron, como su nombre indica, en la antigua Roma hace más de 2.800 años. Después de la eventual desaparición de los romanos, los números todavía se usaban ampliamente durante la Edad Media. Incluso hoy en día, los números romanos prevalecen en nuestra vida cotidiana y aparecen en relojes, títulos de películas y mucho más.

En lugar de números como 1 y 2, los números romanos utilizan letras (predominantemente "I" y "V").

Tabla de números romanos
Usando el cuadro anterior, "I" es 1, "V" es 5, "X" es 10, y así sucesivamente...

Sin embargo, cuando se junta una gran combinación de estos valores, el valor del número se vuelve difícil de leer.

¡Afortunadamente, una secuencia de números romanos se puede convertir fácilmente en números con Python! 


 ```py
numeral_input=input("Cual numero romano quiere convertir a entero: ")
def roman_to_int(numeral):
    entero_convertido=0 #Esto guardara el entero e imprimira al final
    if "CM" in numeral:
            entero_convertido +=900
            numeral=numeral.replace("CM",  "")
    if "CD" in numeral:
            entero_convertido +=400
            numeral=numeral.replace("CD",  "")
    if "XL" in numeral:
            entero_convertido +=90
            numeral=numeral.replace("XC",  "")
    if "XC" in numeral:
            entero_convertido +=40
            numeral=numeral.replace("XL",  "")
    if "IX" in numeral:
            entero_convertido +=9
            numeral=numeral.replace("IX",  "")
    if "IV" in numeral:
            entero_convertido +=4
            numeral=numeral.replace("IV",  "")
    for i in numeral:
        if i == "M":
            entero_convertido +=1000
        elif i == "D":
            entero_convertido +=500
        elif i == "C":
            entero_convertido +=100
        elif i == "L":
            entero_convertido +=50
        elif i == "X":
            entero_convertido +=10
        elif i == "V":
            entero_convertido +=5
        elif i == "I":
            entero_convertido +=1
    print("Los números romanos que ha introducido se traducen por: " + str(entero_convertido) + " !")
roman_to_int(numeral_input)

Árabes	Romano
1	I
2	II
3	III
4	IV
5	V
6	VI
7	VII
8	VIII
9	IX
10	X
11	XI
12	XII
13	XIII
14	XIV
15	XV
16	XVI
17	XVII
18	XVIII
19	XIX
20	XX
21	XXI
22	XXII
23	XXIII
24	XXIV
30	XXX
40	XL
50	L
60	LX
70	LXX
80	LXXX
90	XC
100	C
101	CI
102	CII
200	CC
300	CCC
400	CD
500	D
600	DC
700	DCC
753	DCCLIII
800	DCCC
900	CM
1000	M
1001	MI
1002	MII
1003	MIII
1900	MCM
1999	MCMXCIX
2000	MM
2001	MMI
2002	MMII
2100	MMC
````
![image](https://github.com/BoatCode404/AprendiendoPython/assets/166348131/85b87403-d5ad-49ba-9526-fa47e9836c6c)


# Asi se hacen las funciones , como se retornan y como se usan 👌
```p
# Convertir grados Fahrenheit a Celsius
def fahrenheit_to_celsius(fahrenheit):
    celsius = (fahrenheit - 32) * 5/9
    return celsius

# Sumar 13 grados Celsius a 13 grados Fahrenheit y convertir a Celsius
grados_fahrenheit = 13 + 13
grados_celsius = fahrenheit_to_celsius(grados_fahrenheit)

print(f"La suma de 13 grados Fahrenheit y 13 grados Fahrenheit es equivalente a {grados_celsius:.2f} grados Celsius.")
````

## Explicacion de esta linea 
```py
print(f"La suma de 13 grados Fahrenheit y 13 grados Fahrenheit es equivalente a {grados_celsius:.2f} grados Celsius.")
````
### print(: Esto indica que estamos a punto de imprimir algo en la consola.
### f": Aquí comienza la f-string. Las f-strings se identifican por la letra 'f' antes de las comillas. Esto le indica a Python que esta cadena contendrá expresiones que deben ser evaluadas y formateadas.
### "La suma de 13 grados Fahrenheit y 13 grados Fahrenheit es equivalente a : Esta es la parte de texto estática de la cadena, que se imprimirá tal cual.
### {grados_celsius:.2f}: Esta es la parte de la f-string que contiene una expresión a ser evaluada. {} indica que dentro de estas llaves se debe evaluar una expresión. grados_celsius es ### la variable que contiene la temperatura en grados Celsius. :.2f es una especificación de formato que indica que queremos que el número sea representado con dos decimales después del punto decimal. El .2f significa "2 decimales en formato de punto flotante".
### grados Celsius.": Esta es la parte final del texto estático de la cadena, que se imprimirá tal cual.): Cierra la función print.
