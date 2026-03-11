## Problema: Sistema básico para administrar una lista de empleados

En una práctica de **programación en Python para nivel principiante**, se desea desarrollar un programa sencillo que permita **administrar una lista de empleados** utilizando un **menú de opciones**.

El objetivo del ejercicio es que los estudiantes practiquen el uso de:

* **listas**
* **estructuras condicionales (`if`, `elif`)**
* **ciclos (`while` y `for`)**
* **entrada de datos con teclado (`input`)**

El programa comenzará con una **lista vacía llamada `empleados`**, donde se almacenarán los nombres de los empleados.

El sistema mostrará un **menú dentro de un ciclo `while True`**, el cual permitirá ejecutar varias operaciones hasta que el usuario decida salir del programa.

### Opciones del menú

1. **Agregar empleado**
   El programa solicita el nombre del empleado y lo agrega a la lista `empleados`.

2. **Actualizar empleado**
   El programa solicita el nombre del empleado que se desea cambiar y luego solicita el **nuevo nombre**, reemplazando el anterior en la lista.

3. **Borrar empleado**
   El programa solicita el nombre del empleado que se desea eliminar de la lista.

4. **Ver lista de empleados**
   El programa muestra todos los empleados registrados utilizando un **ciclo `for`** para recorrer la lista.

5. **Salir**
   El programa termina utilizando la instrucción **`break`**.

El menú se repetirá continuamente hasta que el usuario seleccione la opción **5**.

---

# Código en Python (Nivel Principiante)

```python
empleados = []

while True:

    print("\nMENU DE EMPLEADOS")
    print("1. Agregar empleado")
    print("2. Actualizar empleado")
    print("3. Borrar empleado")
    print("4. Ver lista de empleados")
    print("5. Salir")

    opcion = int(input("Ingrese una opcion: "))

    if opcion == 1:
        nombre = input("Ingrese el nombre del empleado: ")
        empleados.append(nombre)
        print("Empleado agregado")

    elif opcion == 2:
        nombre = input("Ingrese el nombre del empleado a actualizar: ")
        nuevo_nombre = input("Ingrese el nuevo nombre del empleado: ")
        indice = empleados.index(nombre)
        empleados[indice] = nuevo_nombre
        print("Empleado actualizado")

    elif opcion == 3:
        nombre = input("Ingrese el nombre del empleado a borrar: ")
        empleados.remove(nombre)
        print("Empleado eliminado")

    elif opcion == 4:
        print("\nLISTA DE EMPLEADOS")
        for empleado in empleados:
            print(empleado)

    elif opcion == 5:
        print("Fin del programa")
        break

    else:
        print("Opcion no valida")
```

---

✅ **Conceptos que se practican en este ejercicio**

* Lista vacía `[]`
* Método **`append()`** para agregar elementos
* Método **`remove()`** para eliminar elementos
* Método **`index()`** para localizar un elemento
* Ciclo **`while True`**
* Condicionales **`if` / `elif`**
* Ciclo **`for`** para recorrer listas
* Uso de **`break`** para terminar el programa

---

Si lo deseas, puedo también generarte una **versión didáctica más completa para estudiantes**, incluyendo:

* **Identificación de variables**
* **Pseudocódigo**
* **Tabla de prueba (entrada / proceso / salida)**
* **Formato de examen + hoja de respuestas para el docente**.
