# Convertir grados Fahrenheit a Celsius 🌡️
```py
def fahrenheit_to_celsius(fahrenheit):
    celsius = (fahrenheit - 32) * 5/9
    return celsius
````

# Calcular IMC (indice de masa corporal) 💪
```py
def calcular_IMC(p,a):
    IMC={p/a**2}
    return IMC
```
# Calcular la hipotenusa de un triangulo 📐
```py
def hipotenusa(l1,l2):
    h=(l1**2+l2**2)**0.5
    return h
n1,n2=float(input("Cual es el primer lado del triangulo: ")),float(input("Cual es el segundo lado del triangulo: "))
h=hipotenusa(n1,n2)
print(f"La hipotenusa del triangulo es : {h}")
````
# Conversion de monedas a dolares 💵
```py
def conversion_monedas_a_USD(m1,m2,m3):
    USD_colombia=0.00026
    USD_brazil=0.20
    USD_peru=0.27
    c=m1*USD_colombia+m2*USD_brazil+m3*USD_peru
    return c
````
# Contrar Movimiento Rectiliano Uniforme (Distancia)📏
```py
def encontrarMru(v,t):
    d=v*t
    return d
````
# funcion de area y semiperimetro de un triangulo con 3 lados ↕️↔️
```py
def area_y_perimetro(l1,l2,l3):
    s=(l1+l2+l3)/2
    a=(s*(s-l1)*(s-l2)*(s-l3))**0.5
    print(a)
    return a
````
# Distancia entre dos puntos 🧷
```py
def distanciaDosPuntos(a1, b1, a2, b2):
    d = ((a2 - a1) ** 2 + (b2 - b1) ** 2) ** 0.5
    return d
````
