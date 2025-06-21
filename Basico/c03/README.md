# String - Cadenas de Texto
Las cadenas de texto son secuencias de caracteres.
No es un tipo de dato primitivo, es una clase que forma parte del propio lenguaje

---

## Declaracion
Se puede declarar un String de dos formas:
- Forma 1: igual que declaramos una variable

``String nombre = "Nico";``

- Forma 2: Ya que es una clase, accediendo al constructor de la misma

``var apellido = new String("Piñera");``

---

## Operaciones basicas
Como es una clase, tiene diferentes metodos que nos sirven como operaciones. 
1. **Concatenacion**: Se puede concatenar String utilizando el `+`. Por ejemplo

``System.out.println(nombre + " " + apellido);``

2. **Longitud**: Para saber la longitud de una cadena se utiliza el metodo ``.length()``. Por ejemplo:

``System.out.println("Longitud del string: "+nombre.length());``

3. Obtener un caracter: Se utiliza el metodo `.charAt()` el cual nos devuelve el caracter en la posicion o indice que se le pase por parametro. El indice puede ir desde [0,length()-1]. Por ejemplo:

``"Caracter en "+ i + ": "+nombre.charAt(i)``

``"Caracter en "+ (nombre.length()-1) + ": "+nombre.charAt(nombre.length()-1)``

