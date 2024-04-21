# Funciones De python 

### type()= Sirve para ver el tipo de dato de una variable
### Srt()= convertir cualquer cosa en una cadena de texto
### int()= convertir cualquer cosa en un entero
### lean()= para contar caracteres de una cadena de texto
### not()= usamos esto para negar un boleando ( si es verdadero lo forzamos que sea falso )
## append()= se usa para agregar un valor a una clave de un diccionario de datos aca vemos un ejemplo de uso :
## elección.aleatoria() = se usa para esocojer un elemento aleatorio de una lista , diccionario , tuplas
```py
# Nuevo jugador a agregar
nuevo_jugador = "Ginny Weasley"

# Agregar el nuevo jugador a la lista de jugadores de Gryffindor
casas["Gryffindor"]["jugadores"].append(nuevo_jugador)
````
- ValueError:
•	Descripción: Ocurre cuando una función espera recibir un tipo de dato específico pero recibe un valor que no es válido para ese tipo de dato.
•	Ejemplo: Si intentas convertir una cadena de texto que no representa un número en un entero usando la función int(), se generará un ValueError.
2.	TypeError:
•	Descripción: Ocurre cuando una operación o función se aplica a un objeto de un tipo incorrecto.
•	Ejemplo: Intentar sumar un entero con una cadena de texto generará un TypeError, ya que la operación de suma no está definida para estos tipos de datos.
3.	ZeroDivisionError:
•	Descripción: Ocurre cuando se intenta dividir un número por cero.
•	Ejemplo: Si intentas realizar una división donde el divisor es cero, como 10 / 0, Python generará un ZeroDivisionError.
4.	IndexError:
•	Descripción: Ocurre cuando se intenta acceder a un índice que está fuera del rango válido de una secuencia (como una lista o una tupla).
•	Ejemplo: Si intentas acceder al elemento en la posición 5 de una lista que solo tiene 3 elementos, Python generará un IndexError.
5.	FileNotFoundError:
•	Descripción: Ocurre cuando se intenta abrir o acceder a un archivo que no existe en el sistema.
•	Ejemplo: Si intentas abrir un archivo para lectura que no se encuentra en la ubicación especificada, Python generará un FileNotFoundError.



- Len()=se usa para contar caracteres
- lower()=se usa para poner todos los caracteres en minisculas
- item()=para buscar en elementos en un diccionarios para imprimirlos
- votos.values(): Este método devuelve una vista de los valores en el diccionario. En otras palabras, devuelve una lista de todos los valores en el diccionario votos
- votos.get: Este método de los diccionarios se utiliza para obtener el valor asociado a una clave específica. Por ejemplo, si tienes el diccionario anterior y quieres obtener el número de votos del 'candidato_2', puedes hacerlo así: votos.get('candidato_2'). Este código devolverá 15, que es el número de votos del 'candidato_2'.
- max(votos, key=votos.get) devolverá la clave asociada al valor máximo en el diccionario votos. En este caso, devuelve la clave del candidato que tiene el máximo número de votos.
