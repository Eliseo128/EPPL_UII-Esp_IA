**Problema: Administración de Empleados con Diccionarios (Python)**

**Contexto:** Ejercicio para principiantes para practicar diccionarios, menús, condicionales, ciclos y entrada de datos.

**Estructura de Datos:**
*   **Diccionario principal:** `empleados`.
*   **Clave:** ID del empleado.
*   **Valor:** Otro diccionario con 5 atributos (nombre, puesto, departamento, edad, salario).

**Funcionamiento:**
Menú repetitivo (`while True`) que ofrece las siguientes opciones:
1.  **Agregar:** Solicitar datos y guardar en el diccionario.
2.  **Actualizar:** Modificar datos de un empleado existente mediante su ID.
3.  **Borrar:** Eliminar un empleado por su ID.
4.  **Ver:** Listar todos los empleados recorriendo el diccionario con `for`.
5.  **Salir:** Terminar el programa con `break`.

## Problema: Administración básica de empleados usando un diccionario

En una práctica de **programación en Python para estudiantes de nivel principiante**, se desea desarrollar un programa sencillo que permita **registrar y administrar empleados utilizando un diccionario**.

El objetivo del ejercicio es practicar:

* Uso de **diccionarios**
* Uso de **menús**
* **estructuras condicionales (`if`, `elif`)**
* **ciclos (`while` y `for`)**
* Entrada de datos mediante **teclado**

El programa iniciará con un **diccionario vacío llamado `empleados`**.
Cada empleado se guardará como un **registro dentro del diccionario**, donde:

* **la clave** será el **ID del empleado**
* **el valor** será otro diccionario con **5 atributos del empleado**

Los **5 atributos** serán:

* nombre
* puesto
* departamento
* edad
* salario

El programa mostrará un **menú que se repetirá dentro de un ciclo `while True`** hasta que el usuario seleccione la opción de salir.

### Opciones del menú

**1. Agregar empleado**
Se solicitan los datos del empleado y se guardan en el diccionario.

**2. Actualizar empleado**
Se solicita el ID del empleado y se ingresan nuevamente sus datos para actualizar la información.

**3. Borrar empleado**
Se solicita el ID del empleado que se desea eliminar del diccionario.

**4. Ver diccionario de empleados**
Se mostrarán todos los empleados registrados utilizando un **ciclo `for`** para recorrer el diccionario.

**5. Salir**
El programa termina usando la instrucción **`break`**.

---

# Código en Python (Nivel Principiante)

```python
empleados = {}

while True:

    print("\nMENU DE EMPLEADOS")
    print("1. Agregar empleado")
    print("2. Actualizar empleado")
    print("3. Borrar empleado")
    print("4. Ver diccionario de empleados")
    print("5. Salir")

    opcion = int(input("Ingrese una opcion: "))

    if opcion == 1:

        id_empleado = input("Ingrese ID del empleado: ")
        nombre = input("Ingrese nombre: ")
        puesto = input("Ingrese puesto: ")
        departamento = input("Ingrese departamento: ")
        edad = input("Ingrese edad: ")
        salario = input("Ingrese salario: ")

        empleados[id_empleado] = {
            "nombre": nombre,
            "puesto": puesto,
            "departamento": departamento,
            "edad": edad,
            "salario": salario
        }

        print("Empleado agregado")

    elif opcion == 2:

        id_empleado = input("Ingrese ID del empleado a actualizar: ")
        nombre = input("Ingrese nuevo nombre: ")
        puesto = input("Ingrese nuevo puesto: ")
        departamento = input("Ingrese nuevo departamento: ")
        edad = input("Ingrese nueva edad: ")
        salario = input("Ingrese nuevo salario: ")

        empleados[id_empleado] = {
            "nombre": nombre,
            "puesto": puesto,
            "departamento": departamento,
            "edad": edad,
            "salario": salario
        }

        print("Empleado actualizado")

    elif opcion == 3:

        id_empleado = input("Ingrese ID del empleado a borrar: ")
        del empleados[id_empleado]

        print("Empleado eliminado")

    elif opcion == 4:

        print("\nDICCIONARIO DE EMPLEADOS")

        for id_empleado in empleados:

            print("ID:", id_empleado)
            print("Nombre:", empleados[id_empleado]["nombre"])
            print("Puesto:", empleados[id_empleado]["puesto"])
            print("Departamento:", empleados[id_empleado]["departamento"])
            print("Edad:", empleados[id_empleado]["edad"])
            print("Salario:", empleados[id_empleado]["salario"])
            print("------------------------")

    elif opcion == 5:

        print("Fin del programa")
        break

    else:
        print("Opcion no valida")
```

---

✅ **Conceptos que practican los estudiantes**

* Diccionarios `{ }`
* Diccionarios dentro de diccionarios
* Acceso a valores por **clave**
* Ciclo **`while True`**
* Condicionales **`if / elif`**
* Recorrido de diccionarios con **`for`**
* Uso de **`break`** para terminar el programa

---

Si lo deseas, también puedo generarte una **versión aún más didáctica para clase**, por ejemplo:

* **Pseudocódigo del ejercicio**
* **Diagrama de flujo**
* **Versión tipo examen (pregunta + espacio para código)**
* **Hoja de respuestas para el docente**
* **Otra práctica similar usando diccionarios de productos o estudiantes**.
