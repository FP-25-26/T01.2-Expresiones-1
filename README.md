# T01.2-Expresiones-1

## Ejercicio 1 - Identificar componentes en expresiones de Python

En cada expresión, identifica y clasifica operadores, literales, variables y funciones. Completa la tabla correspondiente.

✅ Ejemplo:

Expresión:
```python
saludo = "Hola " + nombre.upper()
```

| Elemento   | Tipo                       | Explicación breve                      |
| ---------- | -------------------------- | -------------------------------------- |
| `saludo`   | Variable                   | Recibe el valor de la expresión.       |
| `=`        | Operador (asignación)      | Guarda el resultado en la variable.    |
| `"Hola "`  | Literal (cadena)           | Texto fijo escrito en el código.       |
| `+`        | Operador (aritmético)      | Une las cadenas.                       |
| `nombre`   | Variable                   | Se usa dentro de la llamada a función. |
| `.upper()` | método de cadena           | Convierte la variable en mayúsculas.   |


### Apartado a
Expresión: 

```python
total = precio * cantidad + 5
```
| Elemento   | Tipo                       | Explicación breve                      |
| ---------- | -------------------------- | -------------------------------------- |
|            |                            |                                        |

### Apartado b
Expresión: 

```python
es_mayor = edad >= 18 and tiene_documento
```
| Elemento   | Tipo                       | Explicación breve                      |
| ---------- | -------------------------- | -------------------------------------- |
|            |                            |                                        |

### Apartado c
Expresión: 

```python
mensaje = "Hola, " + nombre + "!"
```
| Elemento   | Tipo                       | Explicación breve                      |
| ---------- | -------------------------- | -------------------------------------- |
|            |                            |                                        |

### Apartado d
Expresión: 

```python
promedio = (nota1 + nota2 + nota3) / 3.0
```
| Elemento   | Tipo                       | Explicación breve                      |
| ---------- | -------------------------- | -------------------------------------- |
|            |                            |                                        |

### Apartado e
Expresión: 

```python
resultado = not (usuario == "admin" or intentos > 3)
```
| Elemento   | Tipo                       | Explicación breve                      |
| ---------- | -------------------------- | -------------------------------------- |
|            |                            |                                        |

### Apartado f
Expresión: 

```python
longitud = len(nombre) + 3
```
| Elemento   | Tipo                       | Explicación breve                      |
| ---------- | -------------------------- | -------------------------------------- |
|            |                            |                                        |

### Apartado g
Expresión: 

```python
resultado = "Hola, " + nombre.strip().upper() + ". Tu número al cuadrado es " + str(numero ** 2) + " y su resto al dividir por 5 es " + str((numero ** 2) % 5)
```
| Elemento   | Tipo                       | Explicación breve                      |
| ---------- | -------------------------- | -------------------------------------- |
|            |                            |                                        |


## Ejercicio 2 - Identificar errores en expresiones en Python

Corrige los errores en las siguientes expresiones.

### Apartado a
Expresión: 

```python
saludo = "Hola" + 5
```
Corrección:
```python
________________________________________________
```

### Apartado b
Expresión: 

```python
nombre = input("Escribe tu nombre: )
```
Corrección: 
```python
________________________________________________
```
### Apartado c
Expresión: 

```python
resultado = pow(3, "2")
```
Corrección: 
```python
________________________________________________
```

### Apartado d
Expresión: 

```python
frase = "Python es genial"
print(frase.upper)
```
Corrección: 
```python
________________________________________________
```

### Apartado e
Expresión: 

```python
edad = "20"
if edad > 18
    print("Mayor de edad")
```
Corrección: 
```python
________________________________________________
```
### Apartado f
Expresión: 

```python
suma = 10 ++ 5
```
Corrección: 
```python
________________________________________________
```
### Apartado g
Expresión: 

```python
lista = [1, 2, 3]
print(lista[3])
```
Corrección: 
```python
________________________________________________
```

### Apartado h
Expresión: 

```python
def saludar()
    print("Hola")
```
Corrección: 
```python
________________________________________________
```

## Ejercicio 3 - Escribir expresiones

Para practicar con expresiones, cree dos módulos `funciones.py` y `funciones_test.py` para escribir y probar las siguientes funciones. Escriba el código de la función en el módulo `funciones` y el código para probarla
en el módulo `funciones_test`.
### Apartado a

Función que reciba como entrada el peso y la estatura de una persona y calcule su índice de masa corporal o IMC, según la siguiente fórmula:
𝐼𝑀𝐶=𝑝𝑒𝑠𝑜/〖𝑒𝑠𝑡𝑎𝑡𝑢𝑟𝑎〗^2 

### Apartado b
Función que calcule el perímetro de un rectángulo dadas su base y su altura.

### Apartado c
Función que reciba los catetos de un triángulo rectángulo y devuelva su hipotenusa.

### Apartado d
Función que dado un año devuelva True si ese año es bisiesto. Un año es bisiesto si es divisible por 400 o si es divisible por 4, pero no por 100.

### Apartado e
Función que convierta un valor dado en grados Fahrenheit a grados Celsius. Recuerda que la fórmula para la conversión es C = (F-32)*5/9<img width="3006" height="476" alt="image" src="https://github.com/user-attachments/assets/c5d4a83c-2d85-49ce-a04b-0e1819a545e6" />
