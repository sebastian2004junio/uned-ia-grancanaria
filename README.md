# UNED · Panel del Grado en Inteligencia Artificial (Gran Canaria)

Adaptación oficial y exhaustiva del panel del estudiante para el **Grado en Ingeniería en Inteligencia Artificial de la UNED** (ETSI Informática), personalizado para el **Centro Asociado de la UNED en Gran Canaria (Las Palmas)** con soporte **PWA offline** e integración con **Google Gemini** y **Google NotebookLM**.

---

## 🔍 Análisis Comparativo y Correcciones Realizadas

### 1. 🏛️ Datos Oficiales y Reales del Centro Asociado de Gran Canaria
* **Web Oficial Real:** [www.unedgrancanaria.es](https://www.unedgrancanaria.es) (NO portales antiguos o erróneos).
* **Dirección Real:** Calle Luis Doreste Silva, nº 101, 4ª planta, 35004 Las Palmas de Gran Canaria.
* **Teléfonos:** 928 231 177 / 928 231 228 | **Email:** `info@las-palmas.uned.es`.
* **Horario de atención:** Lunes a viernes de 10:00 a 13:00 h y de 16:00 a 21:00 h.
* **Aulas Insulares:** Sede Central (Las Palmas) y Aula Universitaria de Gáldar (Norte de Gran Canaria).
* **Plataforma de Tutorías:** Intecca / AVIP (Aulas Virtuales Interactivas con Pizarra) y Microsoft Teams UNED.

### 2. ⏰ Adaptación al Huso Horario de Canarias (WET / UTC+0)
* **Regla Crítica de Exámenes (-1 hora):** Los exámenes de la UNED son simultáneos en toda España. En el Centro Asociado de Gran Canaria comienzan **1 hora antes** que en la Península:
  * **Turno Mañana 1:** **08:00 h** (Península 09:00 h)
  * **Turno Mañana 2:** **10:30 h** (Península 11:30 h)
  * **Turno Tarde 1:** **15:00 h** (Península 16:00 h)
  * **Turno Tarde 2:** **17:30 h** (Península 18:30 h)
* **Reloj Canario en tiempo real:** Barra superior con la hora exacta en Canarias y peninsular.
* **Festivos Insulares y Autonómicos:** Integración en el calendario de los días no lectivos insulares:
  * 30 de Mayo: Día de Canarias
  * 08 de Septiembre: Ntra. Sra. del Pino (Festivo Insular Oficial de Gran Canaria)
  * 24 de Junio: San Juan (Fundación de Las Palmas de Gran Canaria)
  * Martes de Carnaval de Las Palmas de GC

### 3. 📚 Plan de Estudios Oficial (Verificado ANECA · ETSI Informática UNED)
Se han corregido todas las asignaturas para reflejar el plan oficial de la UNED (240 ECTS):
* **1º Curso:** Fundamentos Algebraicos para la IA, Fundamentos de Cálculo para la IA, Fundamentos de Computadores, Fundamentos de Programación (Python), Lógica y Estructuras Discretas, Adquisición, Procesado y Tratamiento de la Información, Fundamentos de Autómatas, Gramáticas y Lenguajes, Fundamentos de Estadística para la IA, Introducción a la Inteligencia Artificial, Programación Orientada a Objetos.
* **2º Curso:** Estructuras de Datos y Algoritmos, Fundamentos de Modelado Estadístico de Datos, Métodos Analíticos para la Toma de Decisiones, Modelado de la Información y Bases de Datos, Modelos Probabilistas y Análisis de Decisiones, Algoritmia para la IA, Infraestructuras Big Data y Cloud, Introducción a la Ingeniería de Software, Sistemas Distribuidos y Procesamiento Paralelo, Sistemas Lógicos para la IA.
* **3º Curso:** Aprendizaje Automático I (Supervisado), Visión Artificial, PLN (NLP), Ingeniería del Conocimiento y Grafos Semánticos, Robótica Inteligente, Aprendizaje Automático II (No Supervisado), Aprendizaje Profundo (Deep Learning), Computación Ubicua y Edge AI, Interacción Persona-Computador, Aspectos Éticos, Jurídicos y Sociales (EU AI Act).
* **4º Curso:** Aprendizaje por Refuerzo y Modelos Generativos (LLMs/Difusión), Ciberseguridad y Gobernanza de IA, Optativas de Especialización, Prácticas Externas Curriculares (12 ECTS) y Trabajo de Fin de Grado (TFG, 12 ECTS).

---

## 🛠️ Todas las Funcionalidades de la Versión Original Preservadas

1. **Menú Lateral Desplegable (*Sidemenu*):** Secciones colapsables con enlaces a portales oficiales (Campus aLF, Secretaría Virtual, Calatayud Exámenes, etc.).
2. **Tarjetas de Acceso Esenciales (*Esenciales*):** Gradientes interactivos para acceso directo a cursos virtuales y recursos clave.
3. **Calendario Mensual Completo Interactivo:**
   * Navegación mes a mes.
   * Detección automática de festivos de Gran Canaria y días de examen.
   * Clic en cualquier día para abrir la **Vista de Día** (`#dayDlg`) con la agenda detallada.
   * Botón para añadir eventos y tareas personalizadas (`#eventModal`).
4. **Cuenta Atrás (*Countdown*):** Días restantes hasta la primera convocatoria oficial de exámenes con fecha, turno canario y sede.
5. **Panel "Esta Semana":** Lista de entregas y tareas con casillas de verificación interactivas para marcar completadas y advertencia de entregas vencidas.
6. **Panel de Exámenes:** Desglose de 1ª y 2ª semana con turnos adaptados a Canarias y filtros ("Solo mis asignaturas" y "Exámenes de tarde").
7. **Cuadrícula Semanal de Tutorías:** Horarios y aulas del Centro Asociado de Gran Canaria con enlaces a Intecca / Teams.
8. **Anillo de Progreso (*Conic Ring*):** Gráfico circular con porcentaje de avance y desglose de créditos FB, OB, OP y TFG.
9. **Ficha Completa de Asignatura y Calculadora:**
   * Selector de 4 estados: Pendiente, Matriculada, Aprobada, Convalidada.
   * Calculadora de nota final ponderando PEC y Examen presencial con comprobación de nota mínima (4.0).
10. **Integración con IA:**
    * **Google NotebookLM:** Generador y descargador en 1 clic de archivos Markdown estructurados listos para subir como fuentes a NotebookLM.
    * **Google Gemini:** Asistente para generar simulacros de examen tipo test UNED, explicaciones conceptuales con Python y planificador de PECs (con opción de clave API local o botón "Copiar para Gemini Web").
11. **PWA (Progressive Web App):** Service Worker offline (`sw.js`), manifest web (`manifest.json`), botón de instalación directa e icono vectorial.
12. **Copia de Seguridad:** Exportación e importación completa en formato JSON.

---

## 📁 Estructura del Proyecto

```text
uned-ia-grancanaria/
├── index.html          # Interfaz completa y estructurada
├── manifest.json       # PWA Manifest
├── sw.js               # Service Worker con caché offline
├── css/
│   └── styles.css      # Hoja de estilos completa con diseño original y modo oscuro
├── js/
│   ├── data.js         # Plan oficial UNED (240 ECTS) y datos de Gran Canaria
│   ├── ai-hub.js       # Integración de Gemini y generador de fuentes NotebookLM
│   └── app.js          # Controlador principal (calendario, progreso, eventos, PWA)
├── icons/
│   └── icon.svg        # Icono de la PWA adaptado
└── README.md           # Esta documentación
```
