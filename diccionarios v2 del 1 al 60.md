Aquí tienes una lista de **30 ejemplos** diferentes siguiendo la estructura solicitada. Aunque mencionaste "numerados del 1 al 20", he completado los **30** para cumplir con tu primera instrucción, manteniendo el formato de gestión CRUD (Crear, Leer, Actualizar, Borrar) con diccionarios anidados en Python.

---

### 1. Gestión de Taller Mecánico
**Contexto:** Controlar las reparaciones de vehículos en un taller.
**Estructura:** Diccionario `taller`. Clave: Matrícula. Valor: {propietario, modelo, falla, estado, presupuesto}.

### 2. Inventario de Biblioteca
**Contexto:** Administración de libros en una biblioteca escolar.
**Estructura:** Diccionario `libros`. Clave: ISBN. Valor: {título, autor, género, año, copias}.

### 3. Registro de Atletas
**Contexto:** Seguimiento de deportistas en un club de alto rendimiento.
**Estructura:** Diccionario `atletas`. Clave: Número de socio. Valor: {nombre, deporte, edad, marca_personal, entrenador}.

### 4. Control de Países
**Contexto:** Base de datos geográfica para estudio estadístico.
**Estructura:** Diccionario `paises`. Clave: Código ISO (ej. "MX"). Valor: {nombre, capital, población, continente, moneda}.

### 5. Catálogo de Videojuegos
**Contexto:** Gestión de una colección personal de juegos.
**Estructura:** Diccionario `videojuegos`. Clave: Título (slug). Valor: {plataforma, desarrollador, año, genero, puntuacion}.

### 6. Sistema de Hospital (Pacientes)
**Contexto:** Administración de ingresos en una clínica médica.
**Estructura:** Diccionario `pacientes`. Clave: DNI/Cédula. Valor: {nombre, edad, diagnostico, doctor_asignado, habitacion}.

### 7. Gestión de Restaurante (Platos)
**Contexto:** Control del menú y precios de un restaurante.
**Estructura:** Diccionario `menu`. Clave: ID_Plato. Valor: {nombre, categoria, precio, ingredientes, calorias}.

### 8. Administración de Hoteles (Habitaciones)
**Contexto:** Control de disponibilidad y servicios de habitaciones.
**Estructura:** Diccionario `habitaciones`. Clave: Número de habitación. Valor: {tipo, capacidad, precio_noche, estado, vista}.

### 9. Control de Flota de Vehículos
**Contexto:** Seguimiento de camiones en una empresa de logística.
**Estructura:** Diccionario `flota`. Clave: ID_Unidad. Valor: {chofer, ruta, capacidad_carga, combustible, modelo}.

### 10. Gestión de Tienda de Mascotas
**Contexto:** Inventario de animales para adopción o venta.
**Estructura:** Diccionario `mascotas`. Clave: ID_Chip. Valor: {especie, raza, edad, salud, precio}.

### 11. Registro de Estudiantes
**Contexto:** Control académico de alumnos en una universidad.
**Estructura:** Diccionario `estudiantes`. Clave: Matrícula. Valor: {nombre, carrera, semestre, promedio, correo}.

### 12. Inmobiliaria (Propiedades)
**Contexto:** Gestión de casas y departamentos en venta/renta.
**Estructura:** Diccionario `propiedades`. Clave: Código Catastral. Valor: {direccion, tipo, metros_cuadrados, precio, dueño}.

### 13. Tienda de Ropa (Productos)
**Contexto:** Inventario de prendas en un local comercial.
**Estructura:** Diccionario `prendas`. Clave: SKU (Código). Valor: {descripcion, talla, color, marca, stock}.

### 14. Gestión de Proyectos de Software
**Contexto:** Seguimiento de tareas en un equipo de desarrollo.
**Estructura:** Diccionario `proyectos`. Clave: ID_Proyecto. Valor: {nombre, lider, lenguaje, fecha_entrega, presupuesto}.

### 15. Catálogo de Películas
**Contexto:** Administración de títulos en una plataforma de streaming.
**Estructura:** Diccionario `peliculas`. Clave: ID_Cinta. Valor: {titulo, director, año, duracion, clasificacion}.

### 16. Gestión de Farmacia (Medicamentos)
**Contexto:** Control de stock y vencimientos de medicinas.
**Estructura:** Diccionario `farmacia`. Clave: Código_Barras. Valor: {nombre, laboratorio, componente_activo, precio, stock}.

### 17. Registro de Gimnasio (Clientes)
**Contexto:** Control de membresías y datos físicos de socios.
**Estructura:** Diccionario `socios`. Clave: ID_Socio. Valor: {nombre, plan, fecha_pago, peso, instructor}.

### 18. Academia de Música (Instrumentos)
**Contexto:** Inventario de instrumentos para préstamo a alumnos.
**Estructura:** Diccionario `instrumentos`. Clave: Serial. Valor: {tipo, marca, estado, año_compra, valor_asegurado}.

### 19. Sistema de Aerolínea (Vuelos)
**Contexto:** Gestión de rutas aéreas y horarios.
**Estructura:** Diccionario `vuelos`. Clave: Número_Vuelo. Valor: {origen, destino, avion, hora_salida, capacidad}.

### 20. Control de Museos (Obras de Arte)
**Contexto:** Registro de piezas en una galería de arte.
**Estructura:** Diccionario `obras`. Clave: ID_Obra. Valor: {titulo, artista, epoca, tecnica, sala_exhibicion}.

### 21. Gestión de Concesionario (Autos)
**Contexto:** Control de autos nuevos y usados para la venta.
**Estructura:** Diccionario `autos`. Clave: VIN (Número de serie). Valor: {marca, modelo, color, kilometraje, precio}.

### 22. Administración de Cursos Online
**Contexto:** Plataforma educativa que gestiona sus cursos.
**Estructura:** Diccionario `cursos`. Clave: ID_Curso. Valor: {titulo, instructor, horas, nivel, precio}.

### 23. Seguimiento de Cultivos (Agricultura)
**Contexto:** Control de siembra en una finca tecnológica.
**Estructura:** Diccionario `cultivos`. Clave: Lote_ID. Valor: {tipo_planta, fecha_siembra, riego, fertilizante, fecha_cosecha}.

### 24. Registro de Eventos (Conciertos)
**Contexto:** Organización de eventos masivos.
**Estructura:** Diccionario `eventos`. Clave: ID_Evento. Valor: {artista, fecha, lugar, aforo, promotor}.

### 25. Control de Gastos Personales
**Contexto:** Seguimiento mensual de finanzas.
**Estructura:** Diccionario `gastos`. Clave: ID_Gasto. Valor: {categoria, concepto, fecha, monto, metodo_pago}.

### 26. Gestión de Refugio de Animales
**Contexto:** Control de perros y gatos rescatados.
**Estructura:** Diccionario `refugio`. Clave: Nombre_Animal. Valor: {especie, fecha_rescate, vacunado, comportamiento, tamaño}.

### 27. Sistema de Cafetería (Insumos)
**Contexto:** Control de stock de granos y suministros.
**Estructura:** Diccionario `insumos`. Clave: ID_Insumo. Valor: {nombre, proveedor, cantidad, unidad_medida, precio_unitario}.

### 28. Administración de Hardware (Servidores)
**Contexto:** Gestión de infraestructura en un Data Center.
**Estructura:** Diccionario `servidores`. Clave: IP_Privada. Valor: {nombre, ram, cpu, almacenamiento, sistema_operativo}.

### 29. Gestión de Estacionamiento
**Contexto:** Control de vehículos en un parking privado.
**Estructura:** Diccionario `parking`. Clave: Placa. Valor: {hora_entrada, dueño, lugar_asignado, tipo_vehiculo, abonado}.

### 30. Registro de Planetas (Astronomía)
**Contexto:** Base de datos para una aplicación de ciencia.
**Estructura:** Diccionario `sistema_solar`. Clave: Nombre. Valor: {masa, distancia_al_sol, lunas, tipo_atmosfera, diametro}.

---

**Funcionamiento general para todos los ejemplos:**
Un bucle `while True` con un menú:
1.  **Agregar:** Pide los 5 atributos y la clave única.
2.  **Actualizar:** Pide la clave, si existe, permite cambiar los atributos.
3.  **Borrar:** Pide la clave y elimina el registro.
4.  **Ver:** Muestra todos los datos formateados.
5.  **Salir:** Rompe el bucle.
6.  


Aquí tienes otros **30 ejemplos adicionales**, numerados del **31 al 60**, siguiendo exactamente la misma estructura para practicar lógica de programación con diccionarios en Python.

---

### 31. Gestión de Barbería (Citas)
**Contexto:** Control de turnos diarios en una peluquería.
**Estructura:** Diccionario `citas`. Clave: ID_Cita. Valor: {cliente, barbero, servicio, hora, costo}.

### 32. Bodega de Vinos (Cava)
**Contexto:** Inventario de una tienda especializada en vinos.
**Estructura:** Diccionario `vinoteca`. Clave: SKU/Código. Valor: {nombre, tipo_uva, año, bodega, precio}.

### 33. Tienda de Libros Usados
**Contexto:** Administración de compra y venta de libros de segunda mano.
**Estructura:** Diccionario `libros_usados`. Clave: ID_Libro. Valor: {titulo, autor, estado_fisico, estante, precio_venta}.

### 34. Centro de Entrenamiento de Drones
**Contexto:** Registro de aeronaves no tripuladas de una academia.
**Estructura:** Diccionario `drones`. Clave: Número de Serie. Valor: {modelo, piloto_asignado, nivel_bateria, horas_vuelo, ultima_revision}.

### 35. Panadería Artesanal (Productos)
**Contexto:** Control de producción y stock de panes diarios.
**Estructura:** Diccionario `panaderia`. Clave: Nombre del Pan. Valor: {tipo_harina, precio, tiempo_horneado, stock, es_vegano}.

### 36. Gestión de Gimnasio (Maquinaria)
**Contexto:** Mantenimiento de equipos en un centro deportivo.
**Estructura:** Diccionario `maquinas`. Clave: Código de Inventario. Valor: {nombre, grupo_muscular, marca, fecha_mantenimiento, estado}.

### 37. Inmobiliaria (Alquiler Vacacional)
**Contexto:** Gestión de reservas de departamentos por temporada.
**Estructura:** Diccionario `alquileres`. Clave: ID_Propiedad. Valor: {ubicacion, capacidad, precio_noche, tiene_wifi, puntuacion}.

### 38. Laboratorio Químico (Elementos)
**Contexto:** Base de datos de reactivos para experimentos escolares.
**Estructura:** Diccionario `elementos`. Clave: Símbolo Químico. Valor: {nombre, numero_atomico, peso_atomico, grupo, estado_agregacion}.

### 39. Tienda de Videojuegos Retro
**Contexto:** Inventario de cartuchos y consolas clásicas.
**Estructura:** Diccionario `retro_games`. Clave: ID_Articulo. Valor: {titulo, plataforma, region, incluye_caja, precio}.

### 40. Agencia de Modelaje (Talentos)
**Contexto:** Registro de perfiles para castings publicitarios.
**Estructura:** Diccionario `modelos`. Clave: ID_Modelo. Valor: {nombre, edad, altura, especialidad, color_ojos}.

### 41. Vivero de Plantas Exóticas
**Contexto:** Seguimiento de cuidados de plantas en un invernadero.
**Estructura:** Diccionario `vivero`. Clave: ID_Planta. Valor: {especie, frecuencia_riego, tipo_luz, abono, precio}.

### 42. Gestión de Entregas (Courier)
**Contexto:** Seguimiento de paquetes en una empresa de mensajería local.
**Estructura:** Diccionario `paquetes`. Clave: Guía de Rastreo. Valor: {remitente, destino, peso_kg, estado_envio, costo_envio}.

### 43. Club de Lectura (Miembros)
**Contexto:** Administración de participantes en un círculo de lectores.
**Estructura:** Diccionario `miembros_club`. Clave: ID_Socio. Valor: {nombre, libro_actual, genero_favorito, fecha_ingreso, asistencia}.

### 44. Academia de Idiomas (Cursos)
**Contexto:** Control de grupos y niveles de enseñanza de lenguas.
**Estructura:** Diccionario `idiomas`. Clave: Código_Curso. Valor: {idioma, nivel, horario, profesor, max_alumnos}.

### 45. Repuestos Automotrices
**Contexto:** Inventario de piezas en una refaccionaria.
**Estructura:** Diccionario `repuestos`. Clave: Número de Parte. Valor: {nombre, marca_auto, categoria, precio, stock}.

### 46. Galería de Fotografía (Obras)
**Contexto:** Registro de fotografías para una exposición artística.
**Estructura:** Diccionario `fotografias`. Clave: ID_Foto. Valor: {fotografo, tecnica, tamaño, año, precio_copia}.

### 47. Registro de Podcast (Episodios)
**Contexto:** Gestión de contenido para un canal de audio.
**Estructura:** Diccionario `podcast`. Clave: ID_Episodio. Valor: {titulo, invitado, duracion_min, fecha_estreno, tema}.

### 48. Bufete de Abogados (Casos)
**Contexto:** Seguimiento de expedientes legales de clientes.
**Estructura:** Diccionario `casos`. Clave: Número de Expediente. Valor: {cliente, abogado_cargo, tipo_caso, estado_legal, honorarios}.

### 49. Gestión de Acuarios (Peces)
**Contexto:** Control de especies en una tienda de peces.
**Estructura:** Diccionario `acuario`. Clave: ID_Pez. Valor: {especie, origen, temperatura_agua, dieta, fecha_ingreso}.

### 50. Inventario de Juguetería
**Contexto:** Control de existencias para la temporada navideña.
**Estructura:** Diccionario `juguetes`. Clave: Código de Barras. Valor: {nombre, rango_edad, marca, precio, stock}.

### 51. Agencia de Viajes (Paquetes Turísticos)
**Contexto:** Administración de promociones de viaje.
**Estructura:** Diccionario `paquetes_viaje`. Clave: ID_Promo. Valor: {destino, dias_estancia, transporte, hotel, precio_total}.

### 52. Gestión de Teatros (Obras en Cartelera)
**Contexto:** Control de producciones teatrales vigentes.
**Estructura:** Diccionario `teatro`. Clave: ID_Obra. Valor: {nombre, director, genero, elenco_principal, duracion}.

### 53. Control de Cámaras de Seguridad
**Contexto:** Monitoreo de infraestructura de vigilancia en un edificio.
**Estructura:** Diccionario `camaras`. Clave: ID_Dispositivo. Valor: {ubicacion, resolucion, estado_online, ip, marca}.

### 54. Registro de Voluntarios (ONG)
**Contexto:** Base de datos de colaboradores para proyectos sociales.
**Estructura:** Diccionario `voluntarios`. Clave: ID_Persona. Valor: {nombre, area_interes, disponibilidad, telefono, fecha_inicio}.

### 55. Gestión de Heladería (Sabores)
**Contexto:** Control de stock y popularidad de helados.
**Estructura:** Diccionario `sabores_helado`. Clave: ID_Sabor. Valor: {nombre, base_leche_o_agua, topping, calorias, stock_litros}.

### 56. Centro de Reparación de Computadoras
**Contexto:** Gestión de tickets de servicio técnico.
**Estructura:** Diccionario `tickets_soporte`. Clave: ID_Ticket. Valor: {cliente, equipo, falla_reportada, tecnico_asignado, presupuesto}.

### 57. Colección de Monedas (Numismática)
**Contexto:** Registro de piezas para coleccionistas.
**Estructura:** Diccionario `monedas`. Clave: ID_Moneda. Valor: {pais, valor_facial, año_emision, rareza, estado_conservacion}.

### 58. Gestión de Cómics y Mangas
**Contexto:** Control de volúmenes en una tienda de historietas.
**Estructura:** Diccionario `comics`. Clave: ISBN_ID. Valor: {titulo, autor, numero_tomo, editorial, precio}.

### 59. Inventario de Ferretería (Herramientas)
**Contexto:** Control de stock de artículos de construcción.
**Estructura:** Diccionario `ferreteria`. Clave: ID_Articulo. Valor: {nombre, categoria, marca, medida, stock}.

### 60. Registro de Mascotas de Concurso
**Contexto:** Inscripción para una competencia de belleza canina/felina.
**Estructura:** Diccionario `concurso_mascotas`. Clave: Número de Inscripción. Valor: {nombre, raza, nombre_dueño, categoria, puntos_acumulados}.

---

**Recordatorio de funcionamiento:**
Todos estos ejemplos se resuelven con el mismo algoritmo lógico:
*   Un `while` para el menú.
*   Un `input()` para seleccionar la opción.
*   Uso de `diccionario[clave] = {subdiccionario}` para **Agregar/Actualizar**.
*   Uso de `del diccionario[clave]` para **Borrar**.
*   Uso de `for clave, valor in diccionario.items():` para **Ver** los datos.
