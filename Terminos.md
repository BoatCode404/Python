# Funciones De Python 

### `type()`: 
Sirve para ver el tipo de dato de una variable

### `str()`: 
Convertir cualquier cosa en una cadena de texto

### `int()`: 
Convertir cualquier cosa en un entero

### `len()`: 
Para contar caracteres de una cadena de texto

### `not()`: 
Usamos esto para negar un booleano (si es verdadero, lo forzamos que sea falso)

### `append()`: 
Se usa para agregar un valor a una clave de un diccionario de datos. Aquí vemos un ejemplo de uso:

# Nuevo jugador a agregar
nuevo_jugador = "Ginny Weasley"

# Agregar el nuevo jugador a la lista de jugadores de Gryffindor
casas["Gryffindor"]["jugadores"].append(nuevo_jugador)

# Errores comunes en Python

- **ValueError:**
  - **Descripción:** Ocurre cuando una función espera recibir un tipo de dato específico pero recibe un valor que no es válido para ese tipo de dato.
  - **Ejemplo:** Si intentas convertir una cadena de texto que no representa un número en un entero usando la función `int()`, se generará un `ValueError`.

- **TypeError:**
  - **Descripción:** Ocurre cuando una operación o función se aplica a un objeto de un tipo incorrecto.
  - **Ejemplo:** Intentar sumar un entero con una cadena de texto generará un `TypeError`, ya que la operación de suma no está definida para estos tipos de datos.

- **ZeroDivisionError:**
  - **Descripción:** Ocurre cuando se intenta dividir un número por cero.
  - **Ejemplo:** Si intentas realizar una división donde el divisor es cero, como `10 / 0`, Python generará un `ZeroDivisionError`.

- **IndexError:**
  - **Descripción:** Ocurre cuando se intenta acceder a un índice que está fuera del rango válido de una secuencia (como una lista o una tupla).
  - **Ejemplo:** Si intentas acceder al elemento en la posición 5 de una lista que solo tiene 3 elementos, Python generará un `IndexError`.

- **FileNotFoundError:**
  - **Descripción:** Ocurre cuando se intenta abrir o acceder a un archivo que no existe en el sistema.
  - **Ejemplo:** Si intentas abrir un archivo para lectura que no se encuentra en la ubicación especificada, Python generará un `FileNotFoundError`.

- `len()`: 
  - Se usa para contar caracteres

- `lower()`: 
  - Se usa para poner todos los caracteres en minúsculas

- `item()`: 
  - Para buscar elementos en un diccionario e imprimirlos

- `votos.values()`: 
  - Este método devuelve una vista de los valores en el diccionario. En otras palabras, devuelve una lista de todos los valores en el diccionario `votos`.

- `votos.get()`: 
  - Este método de los diccionarios se utiliza para obtener el valor asociado a una clave específica. Por ejemplo, si tienes el diccionario anterior y quieres obtener el número de votos del 'candidato_2', puedes hacerlo así: `votos.get('candidato_2')`. Este código devolverá 15, que es el número de votos del 'candidato_2'.

- `max(votos, key=votos.get)`: 
  - Devolverá la clave asociada al valor máximo en el diccionario `votos`. En este caso, devuelve la clave del candidato que tiene el máximo número de votos.

