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

Aquí tienes 35 problemas adicionales (numerados del 26 al 60), siguiendo la misma estructura de menú, contextos variados y requerimientos de lógica de programación (`if`, `elif`, `while`).

---

### 26. Cálculo del Área de un Trapecio
**Contexto:** Un arquitecto necesita calcular superficies de terrenos con forma de trapecio.
**Menú:**
1. Área con bases y altura
2. Perímetro (suma de lados)
3. Base mayor desconocida
4. Salir
**Lógica:** El programa se mantiene en un ciclo `while`. Usar `if/elif` para seleccionar la operación. Solicitar bases y altura según la opción y aplicar la fórmula correspondiente.

### 27. Volumen de un Cono
**Contexto:** Una heladería quiere estimar la capacidad de sus conos de helado.
**Menú:**
1. Volumen del cono
2. Área de la base
3. Altura desconocida
4. Salir
**Lógica:** Bucle `while` para el menú. `if/elif` determina si calcula volumen ($1/3 \pi r^2 h$), área base o despeja la altura.

### 28. Conversión de Ángulos
**Contexto:** Un estudiante de trigonometría necesita cambiar unidades angulares.
**Menú:**
1. Grados a Radianes
2. Radianes a Grados
3. Grados a Minutos sexagesimales
4. Salir
**Lógica:** Ciclo `while` activo. Usar condicionales `if/elif` para aplicar los factores de conversión ($\pi/180$, etc.).

### 29. Cálculo de Trabajo Mecánico
**Contexto:** Un ingeniero calcula la energía transferida al mover objetos.
**Menú:**
1. Calcular Trabajo (Fuerza x Distancia)
2. Calcular Fuerza
3. Calcular Distancia
4. Salir
**Lógica:** El menú se repite con `while`. `if/elif` selecciona la variable a despejar de la fórmula $W = F \cdot d$.

### 30. Conversor de Datos Informáticos
**Contexto:** Un técnico de TI necesita convertir tamaños de archivos.
**Menú:**
1. Megabytes a Gigabytes
2. Gigabytes a Terabytes
3. Kilobytes a Megabytes
4. Salir
**Lógica:** Usar `while` para permitir múltiples conversiones. `if/elif` elige la unidad. Dividir por 1024 en cada paso.

### 31. Cálculo de Potencia Eléctrica
**Contexto:** Un electricista verifica la carga de circuitos domésticos.
**Menú:**
1. Potencia (Voltaje x Corriente)
2. Voltaje (Potencia / Corriente)
3. Corriente (Potencia / Voltaje)
4. Salir
**Lógica:** Ciclo `while`. Validar división por cero. Usar `if/elif` para la fórmula seleccionada ($P = V \cdot I$).

### 32. Propiedades de un Número Entero
**Contexto:** Un profesor de matemáticas quiere analizar números ingresados.
**Menú:**
1. Verificar si es Par o Impar
2. Calcular el Cuadrado del número
3. Calcular el Cubo del número
4. Salir
**Lógica:** El usuario ingresa un número. El menú (`while`) permite elegir qué operación hacer sobre ese número usando `if/elif`.

### 33. Cálculo de Impuestos (IVA)
**Contexto:** Un comerciante necesita agregar impuestos a sus precios.
**Menú:**
1. Calcular IVA (16%)
2. Calcular Precio con IVA
3. Calcular Precio sin IVA (desde el total)
4. Salir
**Lógica:** Bucle `while`. `if/elif` aplica el porcentaje correspondiente según si se quiere solo el impuesto o el total.

### 34. Conversión de Velocidad (m/s a km/h)
**Contexto:** Un físico convierte unidades de velocidad para un informe.
**Menú:**
1. Metros/segundo a Km/hora
2. Km/hora a Metros/segundo
3. Metros/segundo a Millas/hora
4. Salir
**Lógica:** Ciclo `while`. Multiplicar por 3.6 o dividir según la opción seleccionada con `if/elif`.

### 35. Área de un Rombo
**Contexto:** Un diseñador de joyas calcula superficies de gemas con forma de rombo.
**Menú:**
1. Área (Diagonal mayor x menor / 2)
2. Perímetro (4 x lado)
3. Diagonal menor desconocida
4. Salir
**Lógica:** Menú en `while`. Solicitar diagonales o lado. Usar `if/elif` para la fórmula geométrica elegida.

### 36. Energía Potencial Gravitatoria
**Contexto:** Un estudiante calcula la energía de objetos elevados.
**Menú:**
1. Calcular Energía ($m \cdot g \cdot h$)
2. Calcular Masa
3. Calcular Altura
4. Salir
**Lógica:** `while` para el menú. Usar $g = 9.8 m/s^2$. `if/elif` para despejar la variable requerida.

### 37. Costo de Envío según Peso
**Contexto:** Una paquetería cobra tarifas escalonadas.
**Menú:**
1. Envío Estándar (Precio fijo)
2. Envío Express (Doble precio)
3. Envío Internacional (Triple precio)
4. Salir
**Lógica:** Pedir peso del paquete. El menú (`while`) selecciona el tipo de tarifa con `if/elif` y multiplica por el peso.

### 38. Conversión de Eficiencia de Combustible
**Contexto:** Un importador de autos convierte especificaciones de consumo.
**Menú:**
1. Km/Litro a Millas/Galón
2. Millas/Galón a Km/Litro
3. Litros/100km a Km/Litro
4. Salir
**Lógica:** Ciclo `while`. Fórmulas de conversión complejas seleccionadas mediante `if/elif`.

### 39. Segunda Ley de Newton (Fuerza)
**Contexto:** Un laboratorio de física analiza movimiento.
**Menú:**
1. Calcular Fuerza ($m \cdot a$)
2. Calcular Masa
3. Calcular Aceleración
4. Salir
**Lógica:** Menú repetitivo (`while`). `if/elif` para elegir qué variable calcular. Validar que la masa no sea cero si se divide.

### 40. Volumen de una Pirámide
**Contexto:** Un museógrafo calcula el espacio de exhibiciones piramidales.
**Menú:**
1. Pirámide de base cuadrada
2. Pirámide de base rectangular
3. Pirámide de base triangular
4. Salir
**Lógica:** `while` muestra el menú. `if/elif` selecciona la fórmula del área de la base para luego calcular el volumen ($1/3 \cdot Base \cdot altura$).

### 41. Calculadora de Propinas Personalizada
**Contexto:** Un usuario quiere dejar un porcentaje exacto de propina.
**Menú:**
1. Propina del 10%
2. Propina del 15%
3. Propina del 20%
4. Salir
**Lógica:** Pedir monto de la cuenta. El menú (`while`) elige el porcentaje. `if/elif` calcula el valor y el total a pagar.

### 42. Conversión de Presión (Atmósferas a Pascales)
**Contexto:** Un químico estandariza unidades de presión.
**Menú:**
1. Atmósferas a Pascales
2. Pascales a Atmósferas
3. Atmósferas a mmHg
4. Salir
**Lógica:** Ciclo `while`. Usar constantes (1 atm = 101325 Pa). `if/elif` para la conversión elegida.

### 43. Conversión de Edad Detallada
**Contexto:** Un formulario requiere la edad en diferentes unidades.
**Menú:**
1. Años a Meses
2. Años a Semanas
3. Años a Días
4. Salir
**Lógica:** Pedir edad en años. El menú (`while`) permite convertir usando `if/elif` (ej. 1 año = 52 semanas).

### 44. Área de un Hexágono Regular
**Contexto:** Un ingeniero civil diseña baldosas hexagonales.
**Menú:**
1. Área conociendo el lado
2. Área conociendo el apotema
3. Perímetro
4. Salir
**Lógica:** `while` para el menú. `if/elif` selecciona la fórmula geométrica específica del hexágono.

### 45. Cálculo de Interés Compuesto (Un Periodo)
**Contexto:** Un banco muestra proyecciones simples de inversión.
**Menú:**
1. Calcular Interés Ganado
2. Calcular Monto Final
3. Calcular Capital Inicial
4. Salir
**Lógica:** Pedir tasa y tiempo. `if/elif` aplica la fórmula $A = P(1 + r)^t$ según lo que se quiera hallar.

### 46. Conversión de Unidades de Cocina
**Contexto:** Un chef adapta recetas internacionales.
**Menú:**
1. Tazas a Mililitros
2. Cucharadas a Mililitros
3. Onzas líquidas a Mililitros
4. Salir
**Lógica:** Ciclo `while`. Factores fijos (1 taza = 240 ml). `if/elif` para la unidad de origen.

### 47. Comparador de Dos Números
**Contexto:** Un sistema básico debe decidir la relación entre dos valores.
**Menú:**
1. Verificar cuál es Mayor
2. Verificar cuál es Menor
3. Verificar si son Iguales
4. Salir
**Lógica:** Pedir dos números. El menú (`while`) usa `if/elif` para comparar y mostrar el resultado lógico.

### 48. Cálculo de Pintura para Pared
**Contexto:** Un pintor estima cuántos litros necesita comprar.
**Menú:**
1. Litros necesarios (1L cubre 10m²)
2. Costo total de pintura
3. Número de galones (3.78L por galón)
4. Salir
**Lógica:** Pedir alto y ancho de la pared. `if/elif` calcula área y luego la opción elegida (litros, costo o galones).

### 49. Conversión de Frecuencia
**Contexto:** Un técnico de radio ajusta frecuencias de onda.
**Menú:**
1. Hertz a Kilohertz
2. Kilohertz a Megahertz
3. Hertz a Megahertz
4. Salir
**Lógica:** Bucle `while`. Dividir por 1000 o 1,000,000 según la opción `if/elif`.

### 50. Calorías Quemadas por Ejercicio
**Contexto:** Una app de fitness estima gasto energético.
**Menú:**
1. Caminata (4 cal/min)
2. Carrera (10 cal/min)
3. Natación (8 cal/min)
4. Salir
**Lógica:** Pedir minutos de ejercicio. El menú (`while`) selecciona la intensidad. `if/elif` multiplica minutos por la tasa calórica.

### 51. Volumen de un Hemisferio
**Contexto:** Un fabricante de tazones calcula capacidad.
**Menú:**
1. Volumen del hemisferio
2. Área superficial curva
3. Área total (incluyendo base)
4. Salir
**Lógica:** Pedir radio. `while` mantiene el menú. `if/elif` aplica fórmulas de la esfera divididas por 2 o ajustadas.

### 52. Descuento por Volumen de Compra
**Contexto:** Un mayorista ofrece descuentos según cantidad.
**Menú:**
1. Descuento 5% (10-50 unidades)
2. Descuento 10% (51-100 unidades)
3. Descuento 20% (+100 unidades)
4. Salir
**Lógica:** Pedir cantidad y precio unitario. El menú (`while`) simula la selección del tier de descuento con `if/elif` para calcular el total.

### 53. Conversión de Resmas de Papel
**Contexto:** Una oficina gestiona inventario de papel.
**Menú:**
1. Resmas a Hojas (1 resma = 500 hojas)
2. Hojas a Resmas
3. Resmas a Cajas (10 resmas por caja)
4. Salir
**Lógica:** Ciclo `while`. `if/elif` para multiplicar o dividir según la unidad de gestión elegida.

### 54. Cálculo de Aceleración Media
**Contexto:** Un analista de datos de autos mide rendimiento.
**Menú:**
1. Aceleración (Cambio vel / Tiempo)
2. Velocidad Final
3. Tiempo transcurrido
4. Salir
**Lógica:** Pedir velocidades inicial/final y tiempo. `if/elif` despeja la variable faltante en la ecuación de aceleración.

### 55. Determinar Tipo de Triángulo por Lados
**Contexto:** Un profesor de geometría clasifica figuras.
**Menú:**
1. Verificar Equilátero
2. Verificar Isósceles
3. Verificar Escaleno
4. Salir
**Lógica:** Pedir 3 lados. El menú (`while`) permite elegir qué verificar. `if/elif` compara los lados para confirmar la categoría.

### 56. Costo de Estacionamiento por Horas
**Contexto:** Un parqueadero cobra tarifas progresivas.
**Menú:**
1. Tarifa Primera Hora
2. Tarifa Horas Adicionales
3. Costo Total Estimado
4. Salir
**Lógica:** Pedir horas estacionadas. `if/elif` calcula el costo según la lógica de tarifa (ej. primera hora más cara).

### 57. Conversión de Energía (Julios a Calorías)
**Contexto:** Un nutricionista compara energía química y física.
**Menú:**
1. Julios a Calorías
2. Calorías a Julios
3. Julios a Kilocalorías
4. Salir
**Lógica:** `while` para el menú. Factor 1 cal = 4.184 J. `if/elif` selecciona la dirección de la conversión.

### 58. Raíces de Ecuación Cuadrática
**Contexto:** Un estudiante de álgebra resuelve ecuaciones de segundo grado.
**Menú:**
1. Calcular Discriminante
2. Calcular Raíz 1
3. Calcular Raíz 2
4. Salir
**Lógica:** Pedir coeficientes a, b, c. `if/elif` muestra el cálculo seleccionado usando la fórmula general.

### 59. Clasificación de Terremotos (Richter)
**Contexto:** Un sismólogo categoriza eventos sísmicos.
**Menú:**
1. Micro (< 2.0)
2. Menor (2.0 - 3.9)
3. Ligero (4.0 - 4.9)
4. Salir
**Lógica:** Pedir magnitud. El menú (`while`) permite verificar en qué rango cae usando `if/elif` anidados para los límites.

### 60. Precio Final con Impuestos y Descuentos
**Contexto:** Un sistema de punto de venta calcula el ticket final.
**Menú:**
1. Aplicar solo Descuento
2. Aplicar solo Impuesto
3. Aplicar Ambos (Descuento luego Impuesto)
4. Salir
**Lógica:** Pedir precio base, % descuento y % impuesto. `while` mantiene el menú. `if/elif` decide el orden y aplicación de los cálculos financieros.
