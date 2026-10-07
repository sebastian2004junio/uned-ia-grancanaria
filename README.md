# Studyflow · UNED IA Gran Canaria

Recreación e implementación de alta fidelidad 1:1 a partir del diseño de **Figma ("Estudio universitario app / Studyflow")** adaptada para el **Grado en Ingeniería en Inteligencia Artificial de la UNED** (Centro Asociado de Las Palmas de Gran Canaria).

---

## 🚀 Características Principales

1. **🎨 Diseño Studyflow (Figma 1:1):**
   * Paleta moderna SaaS: violeta índigo (`#4F46E5`), fondos suaves (`#F8FAFC`), tarjetas limpias con sombras sutiles y modo oscuro completo.
   * Barra lateral colapsable con accesos rápidos a *Inicio, Asignaturas, Calendario, Mi progreso, Enlaces esenciales* y *Google Notebook*.
   * Barra superior con buscador rápido (`⌘ K` / `Ctrl+K`), botón interactivo de **Modo enfoque** (Pomodoro con sonido ambiente y registro automático de horas) y selector de tema.

2. **📊 Vista "Mi progreso" (`/#progreso`):**
   * Gráfico donut interactivo con progreso sobre los 240 ECTS del grado.
   * Desglose por tipología oficial de créditos (Formación Básica 60 ECTS, Obligatorias 144 ECTS, Optativas 24 ECTS y TFG 12 ECTS).
   * Contador de horas de estudio semanales con meta personalizada y gráfico interactivo de barras.
   * **Simulador de nota media del expediente:** calcula qué calificación requieres en las asignaturas pendientes para obtener tu meta de graduación.

3. **📚 Plan Oficial UNED Gran Canaria (240 ECTS):**
   * Catálogo completo con buscador, filtros por curso (1º a 4º) y por estado (Matriculadas, Aprobadas, Convalidadas, Pendientes).
   * Ficha modal de asignatura con temario, horarios de tutorías en Gran Canaria, cálculo ponderado de PEC y examen presencial.

4. **📅 Calendario Académico & Horarios Canarios:**
   * Sincronización con las convocatorias oficiales de exámenes UNED.
   * **Huso horario de Canarias (-1 hora):** turnos adaptados a las 08:00 h, 10:30 h, 15:00 h y 17:30 h.
   * Festivos autonómicos e insulares (Día de Canarias, Ntra. Sra. del Pino, San Juan, Carnaval).
   * Exportación de agenda a formato estándar `.ics` (compatible con Google Calendar, Apple Calendar y Outlook).

5. **🤖 Google NotebookLM & Gemini AI:**
   * Conexión directa con Google Gemini con clave de API almacenada de forma segura en local.
   * Generación y enlace directo a los cuadernos de NotebookLM preparados para el grado.

6. **📱 Experiencia Multiplataforma (Windows PC + Móvil iOS/Android):**
   * **Windows:** Abre directamente `index.html` en tu navegador o instálalo como app de escritorio.
   * **iPhone / iPad:** Abre en Safari y pulsa *Compartir > Añadir a pantalla de inicio* para usarlo a pantalla completa sin barras.
   * **Android:** Abre en Chrome e instala la aplicación con soporte offline vía Service Worker (`sw.js`).
   * **Copia de seguridad:** Exporta e importa todo tu progreso, notas y eventos en formato JSON.

---

## 📂 Estructura del Proyecto

```text
uned-ia-grancanaria/
├── index.html            # Aplicación web completa y autónoma (PWA SPA)
├── manifest.json         # Configuración PWA y metadatos
├── sw.js                 # Service Worker con caché offline (Network-First)
├── icons/
│   └── icon.svg          # Logotipo vectorial oficial Studyflow
├── studyflow_preview.png # Captura de referencia del diseño Figma
└── README.md             # Esta documentación
```
