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
 x= input("Escriba el caracter que desee:")
 
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
x:input("Escribe un numero:")
x= int
if (x == 0):
  print("Es un numero neutro")
elif ( x>0):
  print("Es un numero positivo")
elif ( x<0):
  print( "Es un numero negativo")
  
```
