# Portafolio 
# Qué es Python?
Python es un lenguaje de programación orientado a objetos de alto nivel con semántica dinámica incorporada, que se utiliza principalmente para desarrollar aplicaciones web y de escritorio.Python es relativamente simple y, por lo tanto, fácil de aprender, ya que requiere una sintaxis única centrada en la legibilidad. Los programadores pueden leer y traducir el código de Python más fácilmente que otros lenguajes.
# Qué es una variable?
En programacion una variable consta de un espacio en el sistema de memoria y un nombre simbólico asociado con ese espacio. Esta brecha contiene una cantidad conocida o desconocida de información o valor.
## Nombrando una variable
La creación de estas variables se realizan a través de un valor de la misma, el operador de asignación en el python es el "="     
Correcta asignacion de la variable:
```python
x=23
```
Incorrecta asignacion de variable:
```python
23=x
```
## Asignando valores a una variable
Luego de a ver creado y nombrado la variable debemos asignar una variable la cual puede ser tipo numerica o textual 
Una cosa que se debe tener muy claro es que al momento de escribir un texto en la variable se debe siempre utilizar las comillas para que asi python identifique que es un texto 
```python
mascotas= "gatos"
```
Cuando se asigna un valor numerico no se necesita usar las comillas
```python
edad =30
```
## Operadores básicos
### Suma
El operador que se utiliza para la suma es "+"
```python
Suma=46+1
print(suma)
[output]47
```
### Resta
El operador que se utiliza en la resta es "-"
```python
Resta=23-7
print(resta)
[output]16
```
### Multiplicación
El operador que se utiliza en la multiplicación es "*"
```python
multiplicacion=6*5
print(multiplicacion)
[output]30
```
### Division

El operador que se utiliza en la division es "/"
```python
Divison=35/7
print(Division)
[outup]5
```

## Módulo
En el operador modulo nos da como resultado el resto de la división entera, el simbolo que se usa para este operador es %
```python
num1=4
num2=18
modulo=num1%num2
print(num1,"%",num2,"=",modulo)
```
Como anteriormente se menciono que el modulo da como resultado el resto de la division entera,aqui esta un ejemplo de como modular con 2 variables

# Tipos de datos en Python
Los tipos de datos en python son los siguientes:
```python
*Numeros enteros (integer)
*Numeros de punto flotante(float)
*texto(cadena de caracteres) (string)
*Booleanos (verdadero y falso)
```

## Integer
En el Integer se utilizara el dato "int" para representarlo al lenguaje de programación seguido del int , este tipo de dato se corresponde con los números enteros.
```python
J= int(14)
print(J)
```
## Float
Este tipo de datos corresponde a números reales en decimales. En Python, el punto "." Y no a la coma”, “. Aquí se usa el comando 'float' para representarlo.
```python
resultado = 6.4 + 4.6
print(resultado)     
print(type(resultado)) # Se imprimirá <class ´float`>
```
## String
Estos son los  datos compuestos por caracteres que representan textos, estas cadenas de texto se representan mediante comillas
```python
Nombre = ´Jorge Freire´
print(Nombre)
Nombre = "Jorge Freire"
print(nombre)
```
## Casting en Python
El casting en python es la técnica que sirve para convertir un dato de un tipo a un tipo de dato diferente
```python
int a str : str(23)
str a int : int (87)
float a int:int (3.1)
```
## List
Una lista es una estructura de datos en Python, que es una secuencia ordenada de elementos que son mutables o editables. Cualquier elemento o valor en la lista se llama elemento. Así como las cadenas se definen como caracteres entre comillas dobles, las listas se definen como valores entre corchetes [ ]
```phyton
Lista=[ "cebolla", "tomate", "pimiento" ]
 print:("lista")
 [output]cebolla,tomate,pimiento
```
## Tuple
Una tupla en python es un conjunto ordenado de elementos encerrados entre paréntesis y separados por comas, casi como una lista, una tupla no puede ser una tupla vacía (no forma parte del elemento interno) y no puede cambiar el orden o los datos en ella.
```python
tuple=[Mouse,Monitor,Parlantes]
print:("tuple")
```
## Dictionary
es un tipo de dato en Python con características especiales que nos permiten almacenar cualquier tipo de valor como enteros, cadenas, listas e incluso otras funciones. Estos diccionarios también nos permiten identificar cada elemento mediante una clave.
```python
diccionario = {'nombre' : 'Jorge', ´Edad´ :20}
print(diccionario)
```
# Tomando decisiones
Las decisiones en pythom son muy importantes para decidir si nuestro programa debe ejecutar un comando o no, pero para ello debe cumplir con algunos requisitos previos, para poder lograr esto en python, usa una instrucción if.
## Sentencia if
La estructura if / elif / else es una forma común de controlar el flujo de un programa, lo que te permite ejecutar bloques de código específicos según el valor de algunos datos. Si la condición que sigue a la palabra clave if se cumple o evalúa como verdadera, el bloque de código se ejecutará.
```python 
salario = 4001
if salario > 3000:
    print("salario mayor que 3000")
elif salario > 4000:
    print("salario mayor que 400")
```
## Ciclo For
En python el ciclo for es una estructua que se  repite una serie de instrucciones por un numero determinado de veces (bucle) estos bucles, como su nombre indica, nos permiten ejecutar una o más líneas de código de forma iterativa.
```python 
print("comienzo")
for_ in [0,1,2]
  print(" hola " , end ="")
  print()
  print ("final")
```
## Ciclo While
Un bucle wile permite repetir la ejecución de un grupo de instrucciones mientras se cumpla una condición es decir, mientras la condición tenga el valor True, se representa de la siguiente manera.
```python 
x = 0
while x < 5:
   print('El valor actual es:', X
   X +=1
```
## Break

## Continue
