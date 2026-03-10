### Problema: Cálculo de áreas de figuras geométricas mediante un menú

En una clase de programación de nivel básico, se desea desarrollar un programa sencillo en **Python** que permita a los estudiantes practicar el uso de **menús, estructuras condicionales (`if`, `elif`) y ciclos (`while`)**.

El programa mostrará en pantalla un **menú con cuatro opciones** para que el usuario seleccione qué operación desea realizar.

Las opciones del menú serán:

1. Calcular el **área de un cuadrado**
2. Calcular el **área de un triángulo**
3. Calcular el **área de un círculo**
4. **Salir del programa**

El usuario deberá **ingresar la opción desde el teclado**.
Dependiendo de la opción seleccionada, el programa solicitará los datos necesarios para calcular el área de la figura correspondiente.

* Para el **cuadrado**, se solicitará el valor del **lado**.
* Para el **triángulo**, se solicitarán **base y altura**.
* Para el **círculo**, se solicitará el **radio**.

El programa se ejecutará **repetidamente dentro de un ciclo `while True`**, mostrando el menú después de cada operación, hasta que el usuario elija la **opción 4 (Salir)**.
Cuando esto ocurra, el programa terminará utilizando la instrucción **`break`**.

---

# Código en Python (Nivel Principiante)

```python
print("CALCULADORA DE AREAS")

while True:

    print("\nMENU DE OPCIONES")
    print("1. Area de un cuadrado")
    print("2. Area de un triangulo")
    print("3. Area de un circulo")
    print("4. Salir")

    opcion = int(input("Ingrese una opcion: "))

    if opcion == 1:
        lado = float(input("Ingrese el valor del lado: "))
        area = lado * lado
        print("El area del cuadrado es:", area)

    elif opcion == 2:
        base = float(input("Ingrese la base: "))
        altura = float(input("Ingrese la altura: "))
        area = (base * altura) / 2
        print("El area del triangulo es:", area)

    elif opcion == 3:
        radio = float(input("Ingrese el radio: "))
        area = 3.1416 * radio * radio
        print("El area del circulo es:", area)

    elif opcion == 4:
        print("Fin del programa")
        break

    else:
        print("Opcion no valida")
```

---

✅ **Conceptos que practican los estudiantes con este ejemplo:**

* Ciclo **`while True`**
* Uso de **menú de opciones**
* Condicionales **`if`, `elif`, `else`**
* Entrada de datos con **`input()`**
* Uso de **`break` para salir del programa**
* Cálculo básico de **áreas geométricas**

---

Si lo deseas, también puedo:

* convertir este ejercicio en **formato de examen para estudiantes**,
* agregar **tabla de pruebas (entrada / proceso / salida)**, o
* generar **3 ejercicios similares con menús** para práctica en clase.
