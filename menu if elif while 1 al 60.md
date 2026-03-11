Aquí tienes una lista de 30 problemas diseñados para nivel básico de programación, estructurados para practicarlos con menús, ciclos `while` y condicionales `if-elif-else`.

---

### Geometría y Áreas

**1. Perímetros de figuras planas**
Desarrolla un menú para calcular el perímetro de:
1. Cuadrado (lado), 2. Rectángulo (base y altura), 3. Círculo (radio). 4. Salir.

**2. Volúmenes de sólidos**
Crea un programa que calcule el volumen de:
1. Cubo (lado), 2. Esfera (radio), 3. Cilindro (radio y altura). 4. Salir.

**3. Áreas de polígonos regulares**
Calcula el área de polígonos de $n$ lados:
1. Pentágono, 2. Hexágono, 3. Octágono. (Requiere apotema y perímetro). 4. Salir.

**4. Propiedades del Círculo**
Dado el radio, permite elegir qué calcular:
1. Diámetro, 2. Circunferencia, 3. Área. 4. Salir.

**5. Superficie lateral de cuerpos 3D**
Calcula el área de las caras externas de:
1. Cubo, 2. Prisma rectangular, 3. Cilindro. 4. Salir.

---

### Conversiones de Unidades

**6. Conversión de Temperaturas**
Transforma grados entre escalas:
1. Celsius a Fahrenheit, 2. Fahrenheit a Celsius, 3. Celsius a Kelvin. 4. Salir.

**7. Conversión de Distancias (Métrico)**
Convierte metros a otras unidades:
1. Kilómetros, 2. Centímetros, 3. Milímetros. 4. Salir.

**8. Sistema Métrico a Inglés**
Convierte medidas de longitud:
1. Metros a Pies, 2. Kilómetros a Millas, 3. Centímetros a Pulgadas. 4. Salir.

**9. Conversión de Masa**
Transforma unidades de peso:
1. Kilogramos a Libras, 2. Kilogramos a Gramos, 3. Libras a Onzas. 4. Salir.

**10. Conversión de Divisas (Monedas)**
Simula un tipo de cambio (ej. basado en dólar):
1. USD a MXN (Peso Mexicano), 2. USD a EUR (Euro), 3. USD a COP (Peso Colombiano). 4. Salir.

**11. Unidades de Tiempo**
Convierte una cantidad de horas a:
1. Minutos, 2. Segundos, 3. Días. 4. Salir.

**12. Almacenamiento Digital**
Convierte Gigabytes (GB) a:
1. Megabytes (MB), 2. Kilobytes (KB), 3. Terabytes (TB). 4. Salir.

---

### Física

**13. Movimiento Rectilíneo Uniforme (MRU)**
Calcula una variable de la fórmula $v = d/t$:
1. Velocidad, 2. Distancia, 3. Tiempo. 4. Salir.

**14. Densidad de Materiales**
Calcula una variable de la fórmula $\rho = m/V$:
1. Densidad, 2. Masa, 3. Volumen. 4. Salir.

**15. Segunda Ley de Newton**
Calcula fuerza, masa o aceleración ($F = m \cdot a$):
1. Fuerza, 2. Masa, 3. Aceleración. 4. Salir.

**16. Presión Física**
Calcula la presión ejercida sobre una superficie ($P = F/A$):
1. Presión, 2. Fuerza, 3. Área. 4. Salir.

**17. Ley de Ohm**
Calcula variables eléctricas ($V = I \cdot R$):
1. Voltaje, 2. Corriente, 3. Resistencia. 4. Salir.

**18. Energía Cinética y Potencial**
Selecciona el cálculo de energía:
1. Energía Cinética ($0.5 \cdot m \cdot v^2$), 2. Energía Potencial ($m \cdot g \cdot h$). 3. Salir.

**19. Potencia Mecánica**
Calcula la potencia ($P = W/t$):
1. Potencia, 2. Trabajo realizado, 3. Tiempo empleado. 4. Salir.

**20. Frecuencia y Período**
Calcula ondas:
1. Frecuencia ($1/T$), 2. Período ($1/f$). 3. Salir.

---

### Matemáticas y Estadística

**21. Calculadora Básica**
Realiza operaciones con dos números:
1. Suma, 2. Resta, 3. Multiplicación, 4. División. 5. Salir.

**22. Promedio de Calificaciones**
Menu de opciones:
1. Ingresar notas y calcular promedio, 2. Determinar si aprobó (>=70). 3. Salir.

**23. Clasificación de Triángulos**
Pide los tres lados y elige:
1. Clasificar por lados (Equilátero, Isósceles, Escaleno), 2. Calcular perímetro. 3. Salir.

**24. Análisis de Números**
Pide un número y elige:
1. Ver si es Par o Impar, 2. Ver si es Positivo o Negativo. 3. Salir.

**25. Ecuación Cuadrática**
Dada la forma $ax^2 + bx + c = 0$:
1. Calcular el discriminante, 2. Calcular las raíces (usando la fórmula general). 3. Salir.

---

### Finanzas y Salud

**26. Índice de Masa Corporal (IMC)**
Calcula el estado de salud:
1. Calcular IMC, 2. Ver clasificación (Bajo peso, Normal, Obesidad). 3. Salir.

**27. Interés Simple**
Calcula el rendimiento de una inversión ($I = P \cdot r \cdot t$):
1. Interés ganado, 2. Monto total al final. 3. Salir.

**28. Calculadora de Descuentos**
En una tienda:
1. Aplicar 10% de descuento, 2. Aplicar 20% de descuento, 3. Aplicar IVA (16%). 4. Salir.

**29. Consumo de Combustible**
Calcula el gasto de un viaje:
1. Consumo medio (km/l), 2. Costo total del viaje (basado en precio/litro). 3. Salir.

**30. Conversor de Cocina**
Útil para recetas:
1. Litros a Mililitros, 2. Tazas a Mililitros, 3. Cucharadas a Mililitros. 4. Salir.

---

### Estructura sugerida para el código (Ejemplo base):

```python
continuar = True
while continuar:
    print("\n--- MENÚ DE OPCIONES ---")
    print("1. Opción A")
    print("2. Opción B")
    print("3. Salir")
    
    opcion = input("Seleccione una opción: ")
    
    if opcion == "1":
        # Lógica de la opción 1
        pass
    elif opcion == "2":
        # Lógica de la opción 2
        pass
    elif opcion == "3":
        print("Saliendo del programa...")
        continuar = False
    else:
        print("Opción no válida, intente de nuevo.")
```

Aquí tienes una segunda lista con otros 30 problemas adicionales (del 31 al 60), variando los temas para cubrir trigonometría, química, astronomía, finanzas avanzadas y lógica de la vida cotidiana.

---

### Trigonometría y Geometría Avanzada

**31. Teorema de Pitágoras**
Permite calcular el lado faltante de un triángulo rectángulo:
1. Calcular la hipotenusa, 2. Calcular un cateto. 3. Salir.

**32. Ángulos**
Dada la medida de un ángulo en grados, elige:
1. Calcular el ángulo complementario, 2. Calcular el ángulo suplementario. 3. Salir.

**33. Áreas de figuras curvas**
Cálculos para figuras circulares específicas:
1. Área de una corona circular, 2. Área de un sector circular (con ángulo). 3. Salir.

**34. Propiedades de los Triángulos**
Suma interna de ángulos y tipos:
1. Calcular el tercer ángulo (dados dos), 2. Calcular el área mediante la Fórmula de Herón. 3. Salir.

**35. Poliedros Regulares**
Calcula el volumen de:
1. Tetraedro, 2. Octaedro, 3. Dodecaedro. 4. Salir.

---

### Astronomía y Gravedad

**36. Peso en otros planetas**
Calcula cuánto pesaría un objeto (usando $P = m \cdot g$) en:
1. La Luna, 2. Marte, 3. Júpiter. 4. Salir.

**37. Distancias Astronómicas**
Convierte años luz a:
1. Kilómetros, 2. Unidades Astronómicas (UA), 3. Millas. 4. Salir.

**38. Ley de Gravitación Universal**
Calcula variables simplificadas entre dos cuerpos:
1. Fuerza gravitatoria, 2. Masa de un cuerpo, 3. Distancia entre ellos. 4. Salir.

---

### Química y Materia

**39. Moles y Masa**
Cálculos químicos básicos:
1. Calcular moles ($masa / masa\_molar$), 2. Calcular masa ($moles \cdot masa\_molar$). 3. Salir.

**40. Escala de pH**
Determina la naturaleza de una sustancia:
1. Ingresar pH y ver si es Ácido, Básico o Neutro, 2. Calcular pOH a partir de pH. 3. Salir.

**41. Ley de los Gases Ideales**
Calcula una variable de $PV = nRT$ (manteniendo constantes las otras):
1. Presión, 2. Volumen, 3. Temperatura. 4. Salir.

**42. Mezclas y Soluciones**
Calcula la concentración:
1. Porcentaje masa/masa, 2. Porcentaje volumen/volumen. 3. Salir.

---

### Finanzas Personales y Negocios

**43. Margen de Ganancia**
Ayuda a un comerciante:
1. Calcular precio de venta (basado en costo y % de margen), 2. Calcular el % de margen real (basado en costo y venta). 3. Salir.

**44. Distribución de Presupuesto**
Divide un ingreso mensual según la regla 50-30-20:
1. Calcular Necesidades (50%), 2. Deseos (30%), 3. Ahorro (20%). 4. Salir.

**45. Cálculo de Propinas**
Para una cuenta de restaurante:
1. Propina del 10%, 2. Propina del 15%, 3. Propina del 20%. 4. Salir.

**46. Salario Neto**
Calcula el pago final:
1. Descontar Impuestos (ej. 15%), 2. Descontar Seguro Social (ej. 5%), 3. Sumar Bonos. 4. Salir.

**47. Comparativa de Precios**
Determina qué producto es más barato por unidad:
1. Producto A (precio y cantidad), 2. Producto B (precio y cantidad), 3. Resultado de cuál conviene. 4. Salir.

---

### Salud y Vida Cotidiana

**48. Frecuencia Cardíaca Máxima**
Calcula el esfuerzo físico:
1. Fórmula para hombres (220 - edad), 2. Fórmula para mujeres (226 - edad). 3. Salir.

**49. Consumo de Agua Diario**
Calcula la hidratación recomendada:
1. Basado en peso corporal (35ml por kg), 2. Basado en actividad física intensa. 3. Salir.

**50. Edad de Mascotas**
Convierte años animales a humanos:
1. Perros (según tamaño), 2. Gatos. 3. Salir.

**51. Calculadora de Sueño**
Calcula a qué hora despertar si te duermes ahora (ciclos de 90 min):
1. Después de 4 ciclos, 2. Después de 5 ciclos, 3. Después de 6 ciclos. 4. Salir.

---

### Termodinámica y Energía

**52. Transferencia de Calor**
Calcula el calor necesario ($Q = m \cdot Ce \cdot \Delta T$):
1. Calor absorbido, 2. Variación de temperatura. 3. Salir.

**53. Eficiencia Energética**
Calcula el consumo de un electrodoméstico:
1. Watts a KWh, 2. Costo mensual según tiempo de uso. 3. Salir.

**54. Velocidad del Sonido**
Calcula la distancia de un rayo:
1. Basado en el tiempo entre relámpago y trueno, 2. Ajuste por temperatura ambiental. 3. Salir.

---

### Lógica y Matemáticas Curiosas

**55. Factorial y Sumatoria**
Elige una operación para un número $n$:
1. Calcular el Factorial ($n!$), 2. Calcular la Sumatoria (de 1 a $n$). 3. Salir.

**56. Tablas de Multiplicar**
Muestra tablas:
1. De un número específico (1 al 10), 2. Tabla de cuadrados de los números. 3. Salir.

**57. Conversión de Bases**
Transformaciones simples:
1. Decimal a Binario, 2. Binario a Decimal. (Para nivel básico). 3. Salir.

---

### Productividad y Varios

**58. Calculadora de Pintura**
Para remodelar una habitación:
1. Calcular metros cuadrados de paredes, 2. Calcular cuántos litros comprar (basado en rendimiento por litro). 3. Salir.

**59. Huella de Carbono (Transporte)**
Estima la emisión de CO2:
1. Viaje en Auto, 2. Viaje en Autobús, 3. Viaje en Avión. 4. Salir.

**60. Rendimiento Académico**
Calcula qué nota necesitas en el examen final para pasar:
1. Ingresar notas actuales y sus pesos (%), 2. Calcular nota mínima requerida. 3. Salir.

---

### Ejemplo de cómo aplicar el `while` y `if` en estos problemas:

Para el problema **31 (Pitágoras)**:
```python
import math

while True:
    print("\n--- TEOREMA DE PITÁGORAS ---")
    print("1. Calcular Hipotenusa")
    print("2. Calcular Cateto")
    print("3. Salir")
    
    op = input("Seleccione: ")
    
    if op == "1":
        a = float(input("Cateto A: "))
        b = float(input("Cateto B: "))
        h = math.sqrt(a**2 + b**2)
        print(f"La hipotenusa es: {h}")
    elif op == "2":
        h = float(input("Hipotenusa: "))
        a = float(input("Cateto conocido: "))
        b = math.sqrt(h**2 - a**2)
        print(f"El otro cateto mide: {b}")
    elif op == "3":
        break
    else:
        print("Opción inválida")
```
