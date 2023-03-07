# Sin-Llorar-en-el_intento

Reto #05: 
Tenemos que tratar de crear en notebook de python un codigo que resuelva algunos problemas planteados en clase

## Vocal minúscula

Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

   ```
n: int
n= int(input("Ingrese un numero entero: "))
a=chr(n)
v='a'or 'e' or 'i' or 'o' or 'u'
if str(a) == str(v):
    print("es un vocal minuscula")
    print(chr(n))
else:
    print("no es una vocal minuscula")
print(chr(n))
  ```
## Cadena de longitus 1

Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no

```
letra= input("ingrese una letra:")
a= ord(letra)
if a%2==0: 
    print("La letra pertenece a un numero par")
else:
    print("la letra pertence a un numero impar")
 ```
 
 ## Digito o no?
 
 Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
 
 ```
 x: float
 x= float(input("Escriba el caracter que desee:"))
 
if(x >= '0' and x <= '9'):
    print("es un digito")
else:
    print("no es un digito")
```

## Un numero Positivo, negativo o neutro

Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

-Positivo: "El número x es positivo"
-Negativo: "El número x es negativo"
-Cero (0): "El número x es el neutro para la suma"

```
x: int
x=int(input("Escribe un numero:"))
if (x == 0.0):
  print("Es un numero neutro")
elif ( x>0.0):
  print("Es un numero positivo")
elif ( x<0.0):
  print("Es un numero negativo")
  
```
 ## Cirulo
 Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo
  
  ```
  x=float
y=float
r=float
r=float(input("digitar el radio: "))
x=float(input("digitar x: "))
y=float(input("digitar y: "))
if (x*x + y*y > r**2):
    print("esta por fuera de la circunferencia de radio  " + str(r))
elif (x*x + y*y  == r**2):
    print("esta justo sobre la circunferencia de radio  " + str(r))
else:
    print("esta dentro de la circunferencia")  
```

## Triangulo o no
Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

```
a: float
b: float
c: float
a= float(input("Longitud del lado 1:"))
b= float(input("longitud del lado 2:"))
c= float(input("longitud del lado 3:"))
if a+b>c and a+c>c and b+c>a :
    print("se puede hacer el triangulo")
else:
    print("no se puede hace el triangulo")
 ```
 
 ## Con esto terminamos los problemas del reto de hoy.
