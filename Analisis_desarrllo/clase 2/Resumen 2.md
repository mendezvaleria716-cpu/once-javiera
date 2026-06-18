## ⚙️ 2. Requerimientos Funcionales (RF)
Representan el comportamiento explícito del software; dictan el **QUÉ** debe ejecutar la aplicación ante determinados estímulos.

* **Fórmula de Redacción Formal:** `El sistema + [obligación: deberá/debe] + [acción en infinitivo] + [entidad u objeto sobre el que recae] + [contexto o restricción]`.

### 🗂️ Taxonomía de los Requerimientos Funcionales
* **Control de Acceso y Seguridad:** Procesos vinculados a la identidad (ej. validación de credenciales institucionales).
* **Procesamiento de Datos:** Operaciones lógicas y matemáticas (ej. cálculo automático del costo total del pedido aplicando el subsidio escolar).
* **Almacenamiento y Persistencia (CRUD):** Registro histórico y salvaguarda de información (ej. guardar el historial de transacciones en la base de datos por un periodo mínimo de un año).
* **Módulos de Notificación:** Mecanismos de alerta (ej. envío de alertas push al dispositivo móvil cuando el menú esté listo para retiro).
* **Generación de Reportes:** Consolidación de datos para la toma de decisiones (ej. exportación de balances de ventas semanales en formatos estructurados como CSV o PDF).
* **Lógica de Negocio y Validación:** Restricciones operativas (ej. impedir la compra si el usuario no cuenta con fondos suficientes en su monedero virtual).

---

## 🎨 3. Requerimientos No Funcionales (RNF)
Determinan los atributos de calidad, rendimiento y comportamiento general; especifican el **CÓMO** operará el sistema. Un requerimiento no funcional sin un indicador cuantitativo es subjetivo e inútil.

### 📊 Clasificación Esencial de los RNF
* **⚡ Velocidad y Rendimiento:** Umbrales de tiempo y eficiencia (ej. las transacciones de pago deben procesarse en menos de 1.5 segundos).
* **🔒 Seguridad Informática:** Protocolos de blindaje (ej. encriptación de datos sensibles en tránsito mediante TLS 1.3).
* **👍 Experiencia y Usabilidad:** Facilidad de adopción (ej. la interfaz gráfica debe permitir realizar un pedido en un máximo de 3 interacciones táctiles).
* **🛡️ Resiliencia y Confiabilidad:** Tolerancia a fallos (ej. garantizar un tiempo de actividad continuo - uptime - del 99.7% durante la jornada escolar).
* **📈 Capacidad de Carga (Escalabilidad):** Soporte ante alta demanda (ej. capacidad para procesar 3,000 peticiones simultáneas durante el horario del descanso).
* **🔧 Facilidad de Mantenimiento:** Estructura limpia de desarrollo (ej. el código fuente debe mantener una cobertura de pruebas automatizadas superior al 85%).
* **📱 Adaptabilidad (Portabilidad):** Despliegue multiplataforma (ej. visualización óptima y responsiva tanto en navegadores de escritorio como en sistemas Android e iOS).
* **📜 Marco Gubernamental y Legal:** Estricto apego a la ley (ej. concordancia total con la normativa nacional de protección de datos de menores de edad).

⚠️ *El dilema del balance técnico (Trade-offs):* Fortalecer la seguridad extrema suele ralentizar los tiempos de respuesta o complejizar la experiencia del usuario; incrementar la escalabilidad impacta directamente en los costos de infraestructura en la nube.

---

## 🏆 4. Atributos de Calidad de Software (ISO/IEC 25010)
Representan las dimensiones macro que evalúan la excelencia de un producto tecnológico:

1. **Pertinencia Funcional:** Grado en que las funciones implementadas cubren con exactitud las necesidades reales del negocio.
2. **Eficiencia en el Desempeño:** Optimización del tiempo de respuesta y de los recursos de hardware utilizados.
3. **Interoperabilidad (Compatibilidad):** Capacidad del software para intercambiar información de forma fluida con otros sistemas sin fricciones.
4. **Centralización en el Usuario (Usabilidad):** Diseño intuitivo, accesible, estético y fácil de comprender para cualquier perfil de usuario.
5. **Estabilidad (Confiabilidad):** Habilidad del sistema para mantenerse operativo y recuperarse eficazmente tras un error inesperado.
6. **Protección Integral (Seguridad):** Salvaguarda de la confidencialidad, la autenticidad y la inmutabilidad de los datos alojados.
7. **Sostenibilidad (Mantenibilidad):** Facilidad con la que el equipo de desarrollo puede corregir fallos, actualizar funciones o realizar pruebas.
8. **Versatilidad de Entorno (Portabilidad):** Capacidad del sistema para migrar e instalarse en diferentes ecosistemas tecnológicos con el mínimo esfuerzo.

---

## 🍏 5. Despliegue Práctico: Caso "SchoolEats" (Colegio San Antonio)

### 👥 Mapa de Actores Vinculados
* **Comunidad Estudiantil:** Consumidores finales del servicio.
* **Equipo de Cocina y Proveedores:** Operadores logísticos de la preparación y despacho.
* **Directivas y Rectoría:** Evaluadores del orden, las finanzas y la nutrición institucional.
* **Acudientes y Padres de Familia:** Proveedores del presupuesto y supervisores de la alimentación.

### 🧪 Estrategia de Levantamiento de Información (Elicitación)
* **Cuestionarios Masivos Digitales:** Ideal para capturar las preferencias y dolores de la masa crítica (Estudiantes y Padres).
* **Etnografía y Observación Directa:** Inmersión en la cocina durante las horas pico para registrar cuellos de botella operativos de los cocineros.
* **Entrevistas Individuales en Profundidad:** Sesiones enfocadas con el Rector para alinear el software con los objetivos institucionales y de presupuesto.

### 📊 Contraste y Mapeo Operativo

| Tipo de Requerimiento | Descripción Aplicada al Proyecto | Atributo ISO 25010 Asociado |
| :--- | :--- | :--- |
| **Requerimiento Funcional** | El estudiante podrá abonar saldo a su cuenta mediante transferencias bancarias digitales. | Pertinencia Funcional |
| **Requerimiento Funcional** | El personal de cocina actualizará el stock disponible de platos desde su panel técnico. | Pertinencia Funcional |
| **Requerimiento No Funcional** | La aplicación debe estar disponible de lunes a viernes de 6:00 AM a 4:00 PM sin interrupciones. | Estabilidad (Confiabilidad) |
| **Requerimiento No Funcional** | Los tiempos de carga de la pasarela de pagos no deben superar los 2 segundos. | Eficiencia en el Desempeño |

🔥 **Factores de Calidad Críticos para "SchoolEats":**
* **Estabilidad (Confiabilidad):** Si el sistema colapsa a la hora del almuerzo, se genera caos logístico en la institución.
* **Centralización en el Usuario (Usabilidad):** Los estudiantes disponen de pocos minutos de descanso; el proceso de compra debe ser inmediato.
* **Protección Integral (Seguridad):** Se administran recursos financieros y datos sensibles de menores de edad.

---

## 🏃 6. Modelado Ágil: Historias de Usuario
Herramienta de desarrollo ágil que describe una funcionalidad desde la perspectiva del valor real que aporta a la persona.

### 📐 El Patrón Narrativo Clásico
* **COMO** `[Rol / Tipo de Usuario]`
* **QUIERO** `[Acción / Característica del Software]`
* **PARA** `[Valor Añadido / Propósito Final]`

### 🌟 El Filtro de Calidad: Acrónimo INVEST
* **I**ndependiente (No depende de otra historia para ser programada).
* **N**egociable (Abierta al diálogo y ajustes entre el cliente y los desarrolladores).
* **V**aliosa (Aporta un beneficio claro e incuestionable al negocio).
* **E**stimable (El equipo técnico puede calcular el esfuerzo y tiempo requerido).
* **S**mall / Pequeña (Se puede diseñar y programar dentro de un ciclo de desarrollo corto o Sprint).
* **T**esteable (Cuenta con reglas claras para validar mediante pruebas si funciona o no).

### 📝 Escenario Práctico de Aplicación
**Historia de Usuario:** > **COMO** estudiante del Colegio San Antonio,
> **QUIERO** consultar la oferta del menú escolar desde mi teléfono móvil,
> **PARA** planificar mi almuerzo con anticipación y asegurar mi plato favorito.

#### 🏁 Criterios de Aceptación (Estructura de Escenarios BDD)

* **Escenario A: Consulta exitosa del día actual.**
  * **DADO** que un estudiante ha iniciado sesión válidamente y se encuentra en la pantalla de inicio;
  * **CUANDO** presiona la opción "Menú del Día";
  * **ENTONCES** la aplicación desplegará la fotografía del plato, el nombre detallado, el valor comercial y el número de porciones que quedan disponibles en la cocina.

* **Escenario B: Gestión de platos sin existencias.**
  * **DADO** que las porciones de un menú específico se han agotado por completo en la cocina;
  * **CUANDO** el estudiante intente visualizar dicho plato en la cartelera digital;
  * **ENTONCES** la interfaz mostrará una etiqueta con el texto "AGOTADO" en color rojo y deshabilitará inmediatamente el botón de compra o reserva.

* **Escenario C: Contingencia por pérdida de conectividad.**
  * **DADO** que el dispositivo móvil del estudiante pierde la conexión a internet mientras usa la app;
  * **CUANDO** intente navegar hacia la sección del menú;
  * **ENTONCES** el sistema cargará los datos guardados en la última sesión exitosa (caché) y mostrará un cintillo informativo superior advirtiendo: *"Visualizando datos sin conexión. La disponibilidad de platos podría variar"*.