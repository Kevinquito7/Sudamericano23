<h1>PYTHON</h1>

<p>Es un lenguaje de programación poderoso, versátil y accesible que ha demostrado ser una herramienta valiosa para una amplia gama de aplicaciones. Su facilidad de uso, legibilidad del código y comunidad activa lo convierten en una opción atractiva tanto para principiantes como para desarrolladores experimentados que buscan una solución eficiente y efectiva para sus proyectos.</p>

![](https://cdn.computerhoy.com/sites/navi.axelspringer.es/public/media/image/2023/04/raspberry-lanza-editor-codigo-aprender-python-lenguaje-ia-3008158.jpg?tf=3840x)

<h5> - Métodos: </h5> 

- len(): Devuelve la longitud de una secuencia.
  
 ```
 cadena = "Hola, mundo!"
longitud = len(cadena)
print(longitud)  # Salida: 12
 ```


- input(): Permite al usuario ingresar datos desde la consola.

 ```
 nombre = input("Ingrese su nombre: ")
print("¡Hola,", nombre, "!")
 ```

- range(): Genera una secuencia de números enteros dentro de un rango especificado.

 ```
 for num in range(1, 6):
    print(num) 
 #Salida:
    1
    2
    3
    4
    5
 ```

- int(), float(): Funciones para convertir valores a enteros, números de punto flotante o cadenas.

```
num_str = "10"
num_int = int(num_str)
print(num_int + 5)  # Salida: 15

num_float = float(num_str)
print(num_float / 2)  # Salida: 5.0
```
- max(), min(): Devuelve el valor máximo o mínimo en una secuencia.

```
numeros = [10, 5, 15, 20, 3]
maximo = max(numeros)
minimo = min(numeros)
print(maximo)  # Salida: 20
print(minimo)  # Salida: 3
```

- sorted(): Devuelve una lista ordenada de elementos de una secuencia.

```
numeros = [10, 5, 15, 20, 3]
numeros_ordenados = sorted(numeros)
print(numeros_ordenados)  # Salida: [3, 5, 10, 15, 20]
```

- sum(): Devuelve la suma de los elementos en una secuencia numérica.

```
numeros = [1, 2, 3, 4, 5]
suma_total = sum(numeros)
print(suma_total)  # Salida: 15
```

<hr>

  - Ejemplos: 

```
1) def suma_dos_numeros():
    # Solicitar al usuario que ingrese dos números
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
    
    # Calcular la suma de los números ingresados
    suma = num1 + num2
    
    # Mostrar el resultado de la suma
    print("La suma es:", suma)
 suma_dos_numeros() 
```

```
2) # Definir el número que queremos verificar si es par o impar
numero = 7

# Verificar si el número es par usando el operador módulo (%)
if numero % 2 == 0:
    print("El número es par.")
else:
    print("El número es impar.")
```

```
3) # Definir una función llamada "multiplicar" que toma dos parámetros "a" y "b"
def multiplicar(a, b):
    # Devolver el resultado de la multiplicación
    return a * b

# Llamar a la función "multiplicar" con los argumentos 4 y 6 y guardar el resultado en "resultado"
resultado = multiplicar(4, 6)

# Imprimir el resultado de la multiplicación en la consola
print("El resultado de la multiplicación es:", resultado)
```



