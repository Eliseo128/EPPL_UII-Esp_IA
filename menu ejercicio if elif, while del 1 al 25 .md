Aquí tienes 25 problemas de programación estructurados como menús, diseñados para practicar `if`, `elif`, `while` y operaciones matemáticas básicas. Cada problema incluye el contexto, las opciones del menú y los requisitos de entrada/salida.

---

### 1. Cálculo de Perímetros de Figuras Planas
**Contexto:** Un profesor de geometría necesita una herramienta para calcular rápidamente los perímetros de figuras básicas.
**Menú:**
1. Perímetro de un cuadrado
2. Perímetro de un rectángulo
3. Perímetro de un triángulo equilátero
4. Salir
**Lógica:** El programa debe usar un ciclo `while` para mostrar el menú repetidamente. Usar `if/elif` para seleccionar la figura. Solicitar los lados correspondientes y mostrar el resultado.

### 2. Cálculo de Volúmenes de Sólidos
**Contexto:** En un almacén, se desea estimar el espacio ocupado por cajas y tanques.
**Menú:**
1. Volumen de un cubo
2. Volumen de una esfera
3. Volumen de un cilindro
4. Salir
**Lógica:** El ciclo `while` mantiene el programa activo. Según la opción (`if/elif`), pedir radio, altura o lado. Calcular y mostrar el volumen.

### 3. Conversor de Temperaturas
**Contexto:** Un laboratorio requiere convertir lecturas de temperatura entre diferentes escalas.
**Menú:**
1. Celsius a Fahrenheit
2. Fahrenheit a Celsius
3. Celsius a Kelvin
4. Salir
**Lógica:** Usar `while` para permitir múltiples conversiones. Con `if/elif`, aplicar la fórmula correspondiente ($F = C \times 1.8 + 32$, etc.) y mostrar el resultado.

### 4. Conversor de Distancias
**Contexto:** Una agencia de viajes necesita convertir distancias para clientes internacionales.
**Menú:**
1. Kilómetros a Millas
2. Millas a Kilómetros
3. Metros a Pies
4. Salir
**Lógica:** El menú se repite con `while`. Seleccionar conversión con `if/elif`. Usar factores de conversión fijos (ej. 1 km = 0.621371 millas).

### 5. Conversor de Divisas (Tipo de Cambio Fijo)
**Contexto:** Un turista quiere saber cuánto dinero tiene en otra moneda.
**Menú:**
1. Dólares a Euros
2. Euros a Dólares
3. Dólares a Pesos Mexicanos
4. Salir
**Lógica:** Ciclo `while` para el menú. `if/elif` para elegir la moneda. Solicitar cantidad y multiplicar por la tasa de cambio definida en el código.

### 6. Cálculo de Densidad
**Contexto:** Un estudiante de química quiere calcular propiedades de materiales.
**Menú:**
1. Calcular Densidad (Masa/Volumen)
2. Calcular Masa (Densidad*Volumen)
3. Calcular Volumen (Masa/Densidad)
4. Salir
**Lógica:** El programa no termina hasta elegir "Salir" (`while`). Usar condicionales para pedir los dos datos conocidos y calcular el tercero.

### 7. Cálculo de Presión
**Contexto:** En un taller mecánico, se necesita calcular la presión ejercida por una fuerza.
**Menú:**
1. Calcular Presión (Fuerza/Área)
2. Calcular Fuerza (Presión*Área)
3. Calcular Área (Fuerza/Presión)
4. Salir
**Lógica:** Estructura de menú con `while`. Validar que el divisor no sea cero. Mostrar el resultado con 2 decimales.

### 8. Cálculo de Velocidad Media
**Contexto:** Un entrenador deportivo quiere analizar el rendimiento de los corredores.
**Menú:**
1. Calcular Velocidad (Distancia/Tiempo)
2. Calcular Distancia (Velocidad*Tiempo)
3. Calcular Tiempo (Distancia/Velocidad)
4. Salir
**Lógica:** Bucle `while` activo. `if/elif` para determinar qué fórmula aplicar. Las unidades son metros y segundos.

### 9. Teorema de Pitágoras
**Contexto:** Un carpintero necesita calcular longitudes de vigas diagonales.
**Menú:**
1. Calcular Hipotenusa
2. Calcular Cateto A
3. Calcular Cateto B
4. Salir
**Lógica:** El menú se muestra en un `while`. Según la opción, solicitar los dos valores conocidos y usar raíz cuadrada para hallar el faltante.

### 10. Propiedades del Círculo
**Contexto:** Una fábrica de platos necesita datos sobre sus productos circulares.
**Menú:**
1. Calcular Área ($\pi r^2$)
2. Calcular Circunferencia ($2 \pi r$)
3. Calcular Diámetro ($2r$)
4. Salir
**Lógica:** Ciclo `while` para el menú. Solicitar el radio. Usar `if/elif` para mostrar solo el cálculo seleccionado.

### 11. Índice de Masa Corporal (IMC)
**Contexto:** Una clínica básica quiere orientar a los pacientes sobre su peso.
**Menú:**
1. Calcular IMC
2. Ver Categoría (Bajo peso, Normal, Sobrepeso, Obesidad)
3. Calcular Peso Ideal
4. Salir
**Lógica:** `while` para el menú. En la opción 2, usar `if/elif` anidados para mostrar el mensaje según el rango del IMC calculado previamente.

### 12. Cálculo de Descuentos en Tienda
**Contexto:** Un comercio aplica descuentos según el tipo de cliente.
**Menú:**
1. Descuento Miembro (10%)
2. Descuento Temporada (20%)
3. Descuento Mayorista (30%)
4. Salir
**Lógica:** El programa pide el precio original. Con `if/elif` aplica el porcentaje según el menú. Muestra precio final y ahorro.

### 13. División de Cuenta con Propina
**Contexto:** Un grupo de amigos quiere dividir la cuenta de un restaurante.
**Menú:**
1. Calcular Propina (15%)
2. Calcular Total con Propina
3. Dividir entre Personas
4. Salir
**Lógica:** `while` mantiene el menú. Solicitar monto de cuenta y número de personas. Usar condicionales para mostrar el dato solicitado.

### 14. Consumo de Combustible de un Vehículo
**Contexto:** Un conductor quiere estimar los costos de su viaje.
**Menú:**
1. Km por Litro
2. Litros necesarios para viaje
3. Costo total del viaje
4. Salir
**Lógica:** Pedir rendimiento del auto y precio de gasolina. Usar `if/elif` para calcular la métrica elegida basada en la distancia del viaje ingresada.

### 15. Conversor de Tiempo
**Contexto:** Un gestor de proyectos necesita convertir duraciones de tareas.
**Menú:**
1. Horas a Minutos
2. Minutos a Segundos
3. Días a Horas
4. Salir
**Lógica:** Bucle `while`. Solicitar la cantidad de tiempo. Multiplicar según la opción elegida con `if/elif` (ej. 1 hora = 60 min).

### 16. Conversor de Peso Corporal
**Contexto:** Un gimnasio registra pesos en diferentes unidades.
**Menú:**
1. Kilogramos a Libras
2. Libras a Kilogramos
3. Gramos a Onzas
4. Salir
**Lógica:** Menú repetitivo (`while`). Fórmulas fijas (1 kg = 2.20462 lbs). Mostrar resultado formateado.

### 17. Ley de Ohm (Electricidad)
**Contexto:** Un técnico electrónico repara circuitos simples.
**Menú:**
1. Calcular Voltaje (I * R)
2. Calcular Corriente (V / R)
3. Calcular Resistencia (V / I)
4. Salir
**Lógica:** `while` para el menú. Validar que no se divida por cero en las opciones 2 y 3. Usar `if/elif` para la lógica de cálculo.

### 18. Energía Cinética
**Contexto:** Un profesor de física ilustra el movimiento de objetos.
**Menú:**
1. Calcular Energía ($0.5 \cdot m \cdot v^2$)
2. Calcular Masa
3. Calcular Velocidad
4. Salir
**Lógica:** Ciclo `while`. Solicitar los datos faltantes según la opción. Para velocidad, usar raíz cuadrada.

### 19. Promedio de Calificaciones
**Contexto:** Un docente quiere calcular el estado académico de un alumno.
**Menú:**
1. Ingresar 3 Notas y Promediar
2. Ver Estado (Aprobado/Reprobado)
3. Nota Necesaria para Aprobar
4. Salir
**Lógica:** `while` para el menú. Guardar las notas en variables. Usar `if/elif` para comparar el promedio contra 60 (o la nota mínima).

### 20. Edad en Diferentes Unidades
**Contexto:** Un juego de curiosidades muestra la edad de formas extrañas.
**Menú:**
1. Años a Días
2. Años a Meses
3. Años a Semanas
4. Salir
**Lógica:** Pedir la edad en años. El menú (`while`) permite elegir la conversión. Asumir año de 365 días para simplificar.

### 21. Diagonal de un Rectángulo
**Contexto:** Un diseñador de pantallas necesita saber el tamaño diagonal.
**Menú:**
1. Calcular Diagonal
2. Calcular Área
3. Calcular Perímetro
4. Salir
**Lógica:** Solicitar base y altura. `if/elif` decide si usa Pitágoras (diagonal), multiplicación (área) o suma de lados (perímetro).

### 22. Área Superficial de un Cilindro
**Contexto:** Una empresa de etiquetas necesita cubrir tanques cilíndricos.
**Menú:**
1. Área Lateral
2. Área Total (Lateral + Bases)
3. Volumen
4. Salir
**Lógica:** Pedir radio y altura. Fórmulas distintas según la opción del menú (`if/elif`). Bucle `while` para repetir consultas.

### 23. Volumen y Área de una Esfera
**Contexto:** Un astrónomo calcula propiedades de planetas asumidos como esferas.
**Menú:**
1. Volumen de la esfera
2. Área superficial de la esfera
3. Radio a partir del Volumen
4. Salir
**Lógica:** `while` activo. Para la opción 3, despejar el radio de la fórmula de volumen (requiere raíz cúbica).

### 24. Cálculo de Interés Simple
**Contexto:** Un asesor financiero muestra proyecciones básicas de ahorro.
**Menú:**
1. Calcular Interés Ganado
2. Calcular Monto Total (Capital + Interés)
3. Calcular Tiempo necesario
4. Salir
**Lógica:** Pedir Capital, Tasa y Tiempo. Usar `if/elif` para mostrar el resultado financiero seleccionado. Fórmula: $I = C \cdot i \cdot t$.

### 25. Hidratación Diaria Recomendada
**Contexto:** Una app de salud sugiere consumo de agua.
**Menú:**
1. Calcular Agua según Peso (35ml por kg)
2. Calcular Agua según Actividad (Baja/Media/Alta)
3. Vasos necesarios (250ml por vaso)
4. Salir
**Lógica:** `while` para el menú. En la opción 2, usar `if/elif` para multiplicar por un factor según la intensidad. Opción 3 divide el total entre 250.

---

**Nota para el estudiante:** En todos los problemas, la estructura base del código en Python debe seguir este patrón:
1.  Iniciar una variable de control (ej. `opcion = 0`).
2.  Iniciar un ciclo `while opcion != 4:` (o el número de salir).
3.  Imprimir el menú.
4.  Leer la `opcion`.
5.  Usar `if`, `elif` para cada caso del menú.
6.  Dentro de cada caso, pedir los `input`, hacer el cálculo y `print` del resultado.
7.  Asegurar que la opción "Salir" rompa el ciclo o termine el programa.
