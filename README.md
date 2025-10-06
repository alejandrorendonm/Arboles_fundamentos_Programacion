# Árbol Binario en Java

## Integrantes del Grupo
- 1152467574 Alejandro Rendon Moncada

---

## ¿Qué es un Árbol Binario?

Un árbol binario es una forma de organizar información donde cada elemento puede tener dos ramificaciones. Es como un árbol genealógico, pero cada persona solo puede tener máximo dos hijos.

En programación lo usamos para guardar números de manera ordenada. La regla es simple:
- Los números más pequeños van hacia la izquierda
- Los números más grandes van hacia la derecha

Por ejemplo, si insertamos los números 50, 30 y 70, quedarían así:

```
    50
   /  \
  30   70
```

Esto hace que sea rápido encontrar números porque no tenemos que revisar todos, solo seguimos la rama correcta.

---

## Cómo Funciona Nuestro Programa

El programa tiene tres clases principales:

### 1. Clase Nodo
Es cada cajita del árbol que guarda un número y sabe quiénes son sus hijos izquierdo y derecho.

### 2. Clase ArbolBinario
Es la que hace todo el trabajo:
- **Insertar**: Coloca números nuevos en el lugar correcto
- **Recorrido Inorden**: Muestra todos los números ordenados de menor a mayor
- **Buscar**: Revisa si un número existe en el árbol

### 3. Clase Main
Muestra el menú en pantalla y permite al usuario elegir qué hacer.

---

## Cómo Ejecutar el Programa

### Requisitos
- Tener Java instalado en la computadora
- Un editor de texto Intellinj o Visual Studio Code

### Pasos

1. Guarda el código en un archivo llamado `Main.java`

2. Abre la terminal o CMD en la carpeta donde guardaste el archivo

3. Compila el programa:
```
javac Main.java
```

4. Ejecuta el programa:
```
java Main
```

---

## Ejemplo de Ejecución

Aquí mostramos cómo se ve el programa cuando lo usas:

```
╔════════════════════════════════════╗
║   ÁRBOL BINARIO - MENÚ PRINCIPAL   ║
╚════════════════════════════════════╝
1. Insertar un número
2. Mostrar recorrido Inorden
3. Buscar un número
4. Salir

Seleccione una opción: 1

Ingrese el número a insertar: 50
Número 50 insertado correctamente.

╔════════════════════════════════════╗
║   ÁRBOL BINARIO - MENÚ PRINCIPAL   ║
╚════════════════════════════════════╝
1. Insertar un número
2. Mostrar recorrido Inorden
3. Buscar un número
4. Salir

Seleccione una opción: 1

Ingrese el número a insertar: 30
Número 30 insertado correctamente.

╔════════════════════════════════════╗
║   ÁRBOL BINARIO - MENÚ PRINCIPAL   ║
╚════════════════════════════════════╝
1. Insertar un número
2. Mostrar recorrido Inorden
3. Buscar un número
4. Salir

Seleccione una opción: 1

Ingrese el número a insertar: 70
Número 70 insertado correctamente.

╔════════════════════════════════════╗
║   ÁRBOL BINARIO - MENÚ PRINCIPAL   ║
╚════════════════════════════════════╝
1. Insertar un número
2. Mostrar recorrido Inorden
3. Buscar un número
4. Salir

Seleccione una opción: 2

Recorrido Inorden: 30 50 70

╔════════════════════════════════════╗
║   ÁRBOL BINARIO - MENÚ PRINCIPAL   ║
╚════════════════════════════════════╝
1. Insertar un número
2. Mostrar recorrido Inorden
3. Buscar un número
4. Salir

Seleccione una opción: 3

Ingrese el número a buscar: 50
El número 50 SÍ existe en el árbol.

╔════════════════════════════════════╗
║   ÁRBOL BINARIO - MENÚ PRINCIPAL   ║
╚════════════════════════════════════╝
1. Insertar un número
2. Mostrar recorrido Inorden
3. Buscar un número
4. Salir

Seleccione una opción: 3

Ingrese el número a buscar: 100
El número 100 NO existe en el árbol.

╔════════════════════════════════════╗
║   ÁRBOL BINARIO - MENÚ PRINCIPAL   ║
╚════════════════════════════════════╝
1. Insertar un número
2. Mostrar recorrido Inorden
3. Buscar un número
4. Salir

Seleccione una opción: 4

¡Gracias por usar el programa!
```

---

## Conceptos Importantes

**Recursión**: Es cuando una función se llama a sí misma. Lo usamos para recorrer todo el árbol.

**Recorrido Inorden**: Es una forma de visitar todos los elementos del árbol que los muestra ordenados de menor a mayor.

**Nodo**: Es cada elemento del árbol que contiene un número y puede tener hasta dos hijos.

---

## Conclusión

Este proyecto nos ayudó a entender cómo funcionan los árboles binarios y cómo se pueden usar para organizar información de forma eficiente. Aprendimos que con estructuras de datos adecuadas podemos hacer búsquedas y organización de manera más rápida que con listas simples.
