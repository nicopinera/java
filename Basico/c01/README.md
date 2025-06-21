# Clase 1

---

## Variables y Constantes
Una variable en java se declara de la siguiente manera:

TipoDato NombreVariable = valor;

Por ejemplo:
```String nombre = "Nicolas";```

```int edad = 22;```

Se puede cambiar el valor de una variable despues de definida solamente nombrando la variable y asignando su nuevo valor. Por ejemplo:

```edad = 23;```

**var** asigna el tipo de variable en la primera instanciacion

```var email = "nicolaspinera@gmail.com";```

Para definir una constante, la cual no puede cambiar su valor despues de definido, se hace con la palabra reservada **final**

```final String EMAIL = "nicolaspinera@gmail.com";```

Por lo general las constantes se nombran en MAYUSCULAS 

---

## Tipos de Datos
Tipos de datos Primitivos:
- **int**: para numeros enteros
- **double**: para numeros con coma y de gran tamaño
- **float**: numeros con coma de tamaño menor que double
- **long**: numeros enteros grandes
- **byte**: para numeros binarios
- **char**: caracteres, se guarda con comillas simples ''
- **boolean**: datos booleanos (true/verdadero o false/falso)
Si se escriben los datos con mayuscula, accedo a la clase (Int en vez de int por ejemplo). String no es un tipo de dato primitivo, es una clase pero se utiliza de manera frecuente

---

## Operadores 
Los operadores nos permiten realizar operaciones entre variables
### Operadores aritmeticos
- Suma: +
- Resta: -
- Multiplicacion: *
- Division: / (Devuele solo el resultado, si las variables son enteras devuelve entero, si alguna es float devuelve un numero con coma)
- Modulo: % (Devuelve el resto de una division)

### Operador de Asignacion
- Asignacion de valor: ```= (a=10)```
- Suma: ```+= (a+=1)```
- Resta: ```-= (a-=1)```
- Multiplicacion: ```*= (a*=2)```
- Division: ```/= (a/=2)```
- Modulo: ```%= (a%=2)```

### Operadores de Comparacion (Relaciones):
Devuelven verdadero o falso segun la comparacion se cumpla o no.
- Igual: ```a == b```
- Distinto: ```a != b```
- Menor que: ```a<b```
- Menor o igual que: ```a<=b```
- Mayor que: ```a>b```
- Mayor o igual que: ```a>=b```

### Operadores de Logicos
Combinan valores booleanos, se puede buscar la tabla de verdad de cada operacion.
- And (Y) Logico: ```Condicion1 && Condicion2```
- Or (O) Logico: ```Condicion1 || Condicion2```
- Not (No) Logico: ```!Condicion1```

### Operadores Unarios
Aplican Sobre un solo valor o variable.
- Valor positivo de una variable: ```+b```
- Valor negativo de una variable: ```-b```
- Incrementar en 1 una variable: ```++b```
- Decrementar en 1 una variable: ```--b```
