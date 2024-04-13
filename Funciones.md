# Convertir grados Fahrenheit a Celsius
```py
def fahrenheit_to_celsius(fahrenheit):
    celsius = (fahrenheit - 32) * 5/9
    return celsius
````

# Calcular IMC (indice de masa corporal) 
```py
def calcular_IMC(p,a):
    IMC={p/a**2}
    return IMC
```
# Calcular la hipotenusa de un triangulo
```py
def hipotenusa(l1,l2):
    h=(l1**2+l2**2)**0.5
    return h
n1,n2=float(input("Cual es el primer lado del triangulo: ")),float(input("Cual es el segundo lado del triangulo: "))
h=hipotenusa(n1,n2)
print(f"La hipotenusa del triangulo es : {h}")
````
