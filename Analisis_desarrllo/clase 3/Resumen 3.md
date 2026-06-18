# 🎯 Compendio de Ingeniería de Requerimientos: Elicitación Estratégica y Diagnóstico de Viabilidad

---

## 📑 SECCIÓN 1: Fundamentos de la Elicitación de Requerimientos

### 🔍 Concepto Clave y Filosofía de Descubrimiento
La **elicitación** trasciende la mera captura pasiva de datos; constituye una investigación profunda y metódica destinada a descubrir las necesidades subyacentes, dolores ocultos y expectativas reales de los usuarios. El analista adopta un rol de consultor y detective tecnológico.

* **Paradoja de la Captura Clásica:** Solicitar directamente una lista de deseos al cliente suele ser ineficaz. El usuario final tiende a proponer soluciones basadas en sus herramientas actuales, en lugar de delimitar con precisión la raíz de sus problemáticas operativas.

> 🛠️ *Enfoque Sistémico:* El objetivo principal no es registrar lo que el cliente solicita explícitamente, sino descifrar el valor estratégico que se busca alcanzar.

### 🌟 Atributos y Competencias Críticas del Analista
Para ejecutar una elicitación de alto impacto, el profesional debe desplegar una serie de habilidades sociocognitivas:

1. **Escucha Comprensiva y Analítica:** Procesar el discurso del interlocutor de manera integral, priorizando el entendimiento antes que la formulación de una respuesta inmediata.
2. **Indagación Iterativa y Curiosidad Activa:** Cuestionar el origen y propósito de cada proceso sin dar por sentado normativas o flujos heredados.
3. **Gestión del Silencio Operacional:** Utilizar las pausas en la conversación como ventanas de oportunidad para que el stakeholder profundice en detalles omitidos.
4. **Validación Sistemática:** Mitigar sesgos personales mediante la contrastación y confirmación explícita de cada suposición con los involucrados.

### 🗻 Anatomía del Descubrimiento: El Fenómeno del Iceberg
* **Nivel Superficial (Explicitado):** Demandas directas de interfaces atractivas o velocidades genéricas.
* **Nivel Intermedio (Tácito):** Motivaciones competitivas, presión del mercado o flujos de trabajo paralelos.
* **Nivel Profundo (Inconsciente o Arraigado):** Dinámicas culturales de la organización, resistencias al cambio de paradigma y dependencias procedimentales no documentadas.

---

## 💬 SECCIÓN 2: Diálogo Dirigido — El Arte de la Entrevista

La entrevista representa un canal de comunicación directa y cualitativa. Su efectividad radica en la planeación y en la capacidad de guiar el intercambio de ideas sin encasillarlo.

### 🎭 Tipologías de Interacción
* **Entrevistas Formales (Estructuradas):** Respaldadas por un cuestionario predefinido e inalterable. Brindan uniformidad, facilitando la comparación estadística en muestras amplias.
* **Conversaciones Exploratorias (No Estructuradas):** Interacciones libres sin un guion rígido, ideales para fases de inmersión inicial donde se busca comprender el ecosistema del negocio.
* **Enfoque Mixto (Semiestructuradas):** La alternativa más eficiente. Combina una agenda de control temática con la flexibilidad de explorar vertientes imprevistas de alto valor.

### 📅 El Ciclo de Vida del Diálogo
```
[1. Fase Preparatoria] ──> [2. Fase de Ejecución] ──> [3. Fase de Procesamiento]
   - Perfilamiento             - Apertura y Rapidez          - Síntesis (< 24 hrs)
   - Guion Base (5-10 q)       - Preguntas Guía/Eco          - Formalización de Requerimientos
```

### ❓ Taxonomía de Preguntas Efectivas
* **Exploratorias (Abiertas):** Diseñadas para obtener narrativa y contexto general (*"¿De qué manera gestionan las incidencias críticas?"*).
* **Confirmatorias (Cerradas):** Orientadas a la obtención de métricas, límites o parámetros exactos (*"¿Cuántas transacciones se procesan en la hora pico?"*).
* **De Focalización (Sondeo):** Destinadas a desmenuzar una afirmación previa (*"Mencionó que el sistema falla frecuentemente; ¿cuál fue el comportamiento en el último evento?"*).

---

## 📊 SECCIÓN 3: Diagnóstico Masivo mediante Encuestas

Instrumentos de recolección asíncrona diseñados para capturar datos cuantitativos de una muestra representativa de la población de usuarios.

* **Escenarios de Aplicación Óptima:** Validación de hipótesis a gran escala, dispersión geográfica de los usuarios o necesidad de respaldar decisiones mediante métricas estadísticas.
* **Contraindicaciones:** Exploración de procesos altamente especializados o cuando se requiere comprender el razonamiento cualitativo del usuario.

### 📐 Principios de Diseño Métrico
* **Optimización de Longitud:** Restringir el instrumento a un rango de 10 a 15 reactivos para asegurar tasas de finalización elevadas.
* **Unidad de Propósito:** Cada reactivo debe evaluar una única variable aislada, evitando preguntas compuestas.
* **Descontaminación Lingüística:** Supresión absoluta de terminología técnica de desarrollo de software para evitar confusión.
* **Escalamiento de Actitudes (Métrica Likert):** Empleo de rangos del 1 al 5 para mapear la intensidad de la opinión (ej. desde *Completamente Desacuerdo* hasta *Totalmente de Acuerdo*).

---

## 👀 SECCIÓN 4: Inmersión en Terreno — Observación Operativa

Análisis contextual donde el especialista se desplaza al entorno real de trabajo para auditar la ejecución de los procesos en tiempo real. Esta técnica expone las discrepancias entre el manual oficial y la práctica diaria.

### 🛠️ Modalidades Metodológicas
1. **Pasiva (Pasivo Absoluto):** Registro de acciones sin interferencia en las actividades del operador.
2. **Interactiva (Participativa):** El analista experimenta el flujo de trabajo ejecutando las actividades bajo supervisión.
3. **Focalizada (Shadowing):** Acompañamiento exhaustivo a un rol específico durante su jornada laboral completa.

> ⚖️ *Consideración Psicológica (Efecto Hawthorne):* Los sujetos tienden a optimizar artificialmente su rendimiento al saberse evaluados. Para mitigar esta desviación, las sesiones deben prolongarse el tiempo suficiente para normalizar la presencia del evaluador en el entorno.

---

## 🧩 SECCIÓN 5: Despliegue Práctico — Triangulación Metodológica

### Escenario: Automatización de un Sistema de Gestión de Biblioteca Escolar

Para consolidar una visión fidedigna de la situación actual, se aplican múltiples técnicas en paralelo:

```
                  ┌────────────────────────┐
                  │ 📝 3 Entrevistas       │ -> Revelan cuellos de botella y 
                  │    (Personal Experto)  │    descontrol de inventario manual.
                  └───────────┬────────────┘
                              │
     ┌────────────────────────┴────────────────────────┐
     ▼                                                 ▼
┌────────────────────────┐                        ┌────────────────────────┐
│ 👁️ Observación de Campo │                        │ 📊 840 Encuestas       │
│    (Horas de Afluencia)│                        │    (Alumnos/Docentes)  │
└───────────┬────────────┘                        └───────────┬────────────┘
            │                                                 │
            └────────────────────────┬────────────────────────┘
                                     ▼
                  ┌────────────────────────┐
                  │ 📈 Requerimientos      │
                  │    Consolidados        │
                  └────────────────────────┘
```

* **Hallazgos Cualitativos:** El registro manual induce colas críticas de espera; los usuarios demandan autonomía de consulta.
* **Hallazgos Cuantificados:** El 82% de la comunidad requiere interacción móvil y el análisis de campo demuestra que los registros en papel consumen una media de 5 minutos por transacción.

### 🔄 Derivación a Especificaciones Técnicas
1. **Atributo Funcional (RF):** La plataforma debe proveer una interfaz adaptativa (Web/Mobile) para que la comunidad estudiantil reserve ejemplares de manera remota.
2. **Atributo No Funcional (RNF):** El tiempo de procesamiento para el registro de préstamos en el mostrador principal no debe exceder los 60 segundos bajo condiciones normales de red.

---

## ⚖️ SECCIÓN 6: Matriz de Evaluación y Análisis de Viabilidad

Filtro metodológico y de control de calidad para garantizar que las solicitudes recopiladas se puedan transformar en un producto de software sustentable.

| Dimensión de Análisis | Criterio de Evaluación Operativa |
| :--- | :--- |
| **🛠️ Factibilidad Técnica** | Disponibilidad de herramientas de desarrollo, compatibilidad de infraestructura y curvas de aprendizaje del equipo de ingeniería. |
| **💰 Sostenibilidad Económica** | Retorno de inversión (ROI), costos de licenciamiento, servidores, mantenimiento a largo plazo y ajuste al presupuesto asignado. |
| **👥 Viabilidad Operacional** | Capacidad de adopción por parte de los usuarios finales, alineación con la cultura corporativa y mitigación del rechazo al nuevo sistema. |
| **📜 Conformidad Legal** | Cumplimiento regulatorio, leyes de protección de datos (ej. GDPR, regulaciones locales), derechos de autor y políticas de accesibilidad. |
| **⏱️ Viabilidad Temporal** | Restricciones de calendario, hitos de entrega críticos y alineación con las ventanas de lanzamiento del negocio. |