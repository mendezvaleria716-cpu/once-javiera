# 📐 Resumen: Curso de Análisis y Diseño de Software

Este documento resume el contenido del curso interactivo alojado en la plataforma, diseñado para enseñar a pensar como un **arquitecto digital** antes de escribir código.

---

## 🗺️ Estructura General y Ruta de Aprendizaje
El curso tiene una duración estimada de **3 horas y 45 minutos** distribuidas en 7 módulos conceptuales:

| Módulo | Nombre | Duración | Tema Principal |
| :--- | :--- | :--- | :--- |
| **Módulo 1** | ¿Por qué importan el análisis y el diseño? | 25 min | La importancia de planificar y la regla del 1-10-100. |
| **Módulo 2** | El ciclo de vida del software | 35 min | Las 6 fases fundamentales por las que pasa un sistema. |
| **Módulo 3** | Metodologías Estructuradas | 30 min | Modelos tradicionales y rígidos (Cascada, V, Espiral). |
| **Módulo 4** | Metodologías Ágiles | 35 min | Marcos de trabajo flexibles (Scrum, Kanban, XP). |
| **Módulo 5** | Taller Práctico | 35 min | Actividad para comparar y elegir la mejor metodología. |
| **Módulo 6** | Lectura dirigida: Requerimientos | 40 min | Qué son y cómo definir las condiciones del cliente. |
| **Módulo 7** | Reto Final y Reflexión | 15 min | Proyecto práctico de aplicación y cierre del curso. |

---

## 🔍 Contenido Detallado por Módulos

### 1️⃣ ¿Por qué importan el análisis y el diseño?
* **Analogía de la construcción:** No se pueden poner ladrillos sin un plano; de igual forma, no se programa sin analizar.
* **Estadística clave:** El **66%** de los proyectos de software fracasan o tienen problemas graves debido a requerimientos mal definidos.
* **Definiciones clave:**
  * **Análisis:** Define el **QUÉ** se va a construir (entender el problema).
  * **Diseño:** Define el **CÓMO** se va a construir (planear la solución).
* **La regla del 1-10-100:** Arreglar un error en *Análisis* cuesta $1, en *Diseño* $10, en *Programación* $100, y en *Producción* $1000+.
* **Caso real:** En 1999, la NASA perdió la sonda *Mars Climate Orbiter* ($327M) porque un equipo usó pies y otro metros por falta de análisis en las interfaces.

### 2️⃣ El ciclo de vida del software
El software pasa por etapas desde que nace como una idea hasta que se vuelve obsoleto. Se compone de **6 fases**:
1. **Análisis de Requerimientos:** Entrevistar clientes y crear la *Especificación de Requerimientos*.
2. **Diseño:** Planear la arquitectura, módulos, bases de datos e interfaces.
3. **Implementación (Programación):** Escritura del código base.
4. **Pruebas:** Encontrar fallos y verificar el comportamiento correcto.
5. **Despliegue:** Poner el sistema en funcionamiento real para el usuario.
6. **Mantenimiento:** Corregir errores del uso diario y agregar nuevas mejoras.

### 3️⃣ Metodologías Estructuradas
Se basan en **planificar todo desde el principio y seguir el plan**. Son ideales para sistemas críticos (aviones, hospitales, bancos).
* **Modelo Cascada (Waterfall):** Lineal y rígido. Cada fase debe terminar por completo para iniciar la siguiente.
* **Modelo en V:** Variante de cascada donde cada fase de desarrollo tiene una fase de pruebas correspondiente de forma simétrica.
* **Modelo Espiral:** Centrado en el **análisis de riesgos**, mejorando el producto mediante vueltas o iteraciones sucesivas.

### 4️⃣ Metodologías Ágiles
Nacen en 2001 con el *Manifiesto Ágil*. Priorizan responder al cambio, el software funcional y la colaboración sobre los procesos rígidos.
* **Scrum:** Trabaja con *Sprints* (ciclos de 1-4 semanas), reuniones diarias (*Daily*) y roles definidos (*Product Owner*, *Scrum Master*, *Developer*).
* **Kanban:** Tablero visual por columnas (*Por hacer, Haciendo, Probando, Hecho*) que limita el trabajo en curso para evitar cuellos de botella.
* **XP (Extreme Programming):** Enfoque técnico que usa programación en parejas, desarrollo guiado por pruebas (TDD) y refactorización.

### 5️⃣ Taller Práctico
Sección interactiva para aprender a diagnosticar qué marco usar:
* **Estructurado:** Requerimientos fijos, baja incertidumbre, consecuencias críticas en fallos.
* **Ágil:** Alta incertidumbre, mercados cambiantes, necesidad de entregas rápidas.

### 6️⃣ Lectura dirigida: ¿Qué es un requerimiento?
Un requerimiento es la descripción de lo que el sistema debe hacer o una restricción que debe cumplir (ej. los ingredientes o tiempo de entrega de una pizza).
* **Requerimientos Funcionales:** Lo que el sistema hace (*"Permitir consultar notas"*).
* **Requerimientos No Funcionales:** Propiedades o restricciones (*"Cargar en menos de 2 segundos"*, *"Seguridad con cifrado"*).
* **Lección:** Deben ser específicos, medibles y venir de múltiples fuentes (usuarios, administradores, técnicos).

### 7️⃣ 🏆 Reto Final y Reflexión
El curso cierra con una **Misión Práctica**: Diseñar el análisis inicial para un sistema escolar (a elegir entre *Biblioteca digital, Control de notas, Inscripción a extracurriculares o Reservas de comedor*), el cual debe incluir:
1. Descripción del problema.
2. 5 requerimientos funcionales.
3. 3 requerimientos no funcionales medibles.
4. Lista de personas a entrevistar.
5. Justificación de la metodología elegida (Ágil o Estructurada).