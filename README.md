# 🎓 SICE-CBA: Evolución del Control de Estudios (CBA vs. CEO)

> **U.E.P. Colegio Bellas Artes**  
> Maracaibo, Estado Zulia, Venezuela · Código DEA: **S0432D2305**  
> Repositorio Oficial de la Presentación Institucional: [GitHub](https://github.com/themiguedev/presentacion-SICE-CBA)

---

## 📌 Descripción del Proyecto

Esta presentación ejecutiva e interactiva expone de forma directa, visual y concisa la transición tecnológica desde el sistema anterior **CEO** (*Control Estudiantil Online / Lidsoftware*, basado en PHP clásico de 2012) hacia la nueva plataforma **SICE-CBA** (2026+), desarrollada como una **Single Page Application (SPA)** reactiva, con base de datos nativa **PostgreSQL 16** e infraestructura **100% On-Premise** dentro de la red del colegio.

El sistema se encuentra actualmente en **fase activa de validación y pruebas locales**, con el objetivo de ser desplegado de manera definitiva en los **servidores propios del Colegio Bellas Artes**.

---

## 🖥️ Estructura de Diapositivas (6 Módulos Clave)

1. **Portada & Estado del Proyecto:**
   - Presentación institucional, escudo oficial y distinción del plan: *Fase 1: Pruebas Locales* ➔ *Fase 2: Despliegue en Servidores del Colegio*.

2. **De CEO a SICE-CBA:**
   - **Infraestructura:** Servidores físicos vulnerables a fluctuaciones eléctricas vs. Sistema y base de datos integrados en un mismo servidor con opción de enlace a la nube sincronizado para garantizar máxima estabilidad.
   - **Velocidad y Fluidez:** Recargas lentas de pantalla (F5) vs. Guardado continuo celda por celda sin pérdida de notas.
   - **Comunicación:** Módulo integral de mensajería y comunicados multicanal (campanita web, email, WhatsApp/SMS, segmentación por rol/nivel, alertas urgentes y auditoría de envíos).

3. **Cara a Cara Visual: Escritorio y Centro de Comando:**
   - Comparativa 50/50 con capturas reales de alta definición entre el panel estático de CEO y el *Academic Pulse Hero* en tiempo real de SICE-CBA con buscador global (Ctrl+K).

4. **Automatización de Tareas Recurrentes por Rol (Documento Institucional CBA):**
   - **Directora:** Estrategias por curso/docente, asistencia, conducta, **Doble Pensum Académico (Promedio MPPE y Promedio CBA)**, cuadros estadísticos y reporte de **Grupos CRP** (inscripción y notas).
   - **Coordinación Docente de Inicial:** Indicadores evaluados, **Indicadores Actitudinales**, consultas de evaluación por estudiante y curso, y estadísticas formativas en escala literal (A a E).
   - **Coordinación Docente de Primaria:** Indicadores por curso/docente, asistencia, disciplina, **Doble Pensum (MPPE y CBA)**, cuadros estadísticos y escala cualitativa (A, L, P, I).
   - **Coordinación Docente de Media General:** Registro de estrategias evaluadas, asistencia, disciplina, **Doble Pensum (escala vigesimal 01 a 20)**, cuadros estadísticos y **Grupos CRP**.
   - **Departamento de Orientación (7 Tareas):** Reporte de indicadores evaluados (por nivel, curso y estudiante), reporte de estrategias cargadas (por curso y estudiante), registros de conducta y de asistencia (por nivel, curso y estudiante), y cuadros estadísticos de indicadores (con **Doble Pensum: MPPE y CBA**), de asistencia y de conducta por curso.

5. **Plan de Despliegue a Servidores del Plantel & Preguntas y Respuestas:**
   - Ruta de 4 fases hacia la producción definitiva en la infraestructura del colegio y espacio abierto para directivos y docentes.

---

## ✨ Animaciones y Transiciones entre Diapositivas

La presentación cuenta con un motor de transiciones cinemáticas fluidas y aceleradas por hardware (GPU), permitiendo alternar dinámicamente entre 4 estilos desde el selector superior o la tecla `M`:

1. **↔️ Deslizamiento (Slide - Por defecto):** Desplazamiento horizontal fluido y espacial con profundidad 3D y atenuación de bordes.
2. **🔍 Zoom & Fade:** Desvanecimiento cinemático con escala progresiva para máxima elegancia.
3. **🧊 Cubo 3D:** Rotación tridimensional sobre el eje Y con perspectiva envolvente.
4. **↕️ Vertical:** Desplazamiento vertical tipo deck ejecutivo.

Además, los elementos internos de cada diapositiva (títulos, métricas, tarjetas comparativas y paneles de rol) incorporan **animaciones de entrada escalonadas (staggered build-in)** para una experiencia visual de nivel profesional.

---

## 📱 Diseño 100% Responsive & Soporte Multiplataforma

La presentación ha sido diseñada y optimizada para adaptarse fluidamente a cualquier resolución y dispositivo:
- **💻 Pantallas de Escritorio y Laptops (>1200px / 992px):** Visualización ejecutiva panorámica con cuadrículas en paralelo (comparativas 50/50, centros de comando y tableros interactivos por rol).
- **📱 Tablets (Vertical y Horizontal - 768px a 992px):** Reorganización automática de columnas a flujos verticales, tipografía equilibrada y navegación táctil fluida.
- **📲 Smartphones (Hasta 540px):** Controles compactos en barras superior e inferior, márgenes optimizados, scroll vertical fluido e independiente dentro de cada diapositiva (`-webkit-overflow-scrolling: touch;`), e interfaces de tareas interactivas adaptadas a pantallas pequeñas.
- **🔄 Modo Horizontal Móvil (Landscape / <620px alto):** Modos compactos para barras de control que maximizan el área de lectura en teléfonos en posición horizontal.
- **👆 Gestos Táctiles (Swipe):** Detección inteligente de deslizamiento horizontal que discrimina gestos de scroll vertical para una navegación libre de saltos accidentales.

---

## 🕹️ Navegación y Atajos de Teclado

| Tecla / Acción | Función |
| :--- | :--- |
| **◀ / ▶** o **Espacio** | Avanzar o retroceder diapositiva con transición animada |
| **M** | Alternar estilo de animación de transición (Slide, Zoom, Cubo 3D, Vertical) |
| **D** | Alternar entre Modo Azul Marino CBA y Modo Claro de Alto Contraste |
| **F** | Activar / Desactivar Pantalla Completa |
| **T** | Abrir / Cerrar Índice Lateral de Diapositivas |
| **Home / End** | Ir directamente a la primera o última diapositiva |
| **Clic en Imagen** | Zoom en Alta Definición (Cerrar con Esc o botón cerrar) |
| **Swipe Táctil** | Navegación gestual táctil para tablets y pantallas táctiles |

---

## 🚀 Cómo Visualizar la Presentación

### Modo Local (Doble Clic):
Simplemente abre el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Microsoft Edge, Firefox, Safari). No requiere conexión a internet, servidores adicionales ni dependencias externas.

---

*Desarrollado para la Unidad Educativa Bellas Artes · 2026*
