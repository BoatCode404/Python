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