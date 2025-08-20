# Roadmap 3 meses: Qlik Sense, Mashups, Extensiones y Python

**Horario sugerido diario:** 2h (30 min teoría/lectura + 1h práctica + 30 min revisión)  
**Formato:** Lectura de libros + práctica en Qlik Sense + ejercicios web/Python + mashups/extensiones

---

## Mes 1: Fundamentos Web y Qlik Sense Mashups

### Semana 1: HTML y CSS básico
**Libros/documentos recomendados:**
- “HTML and CSS: Design and Build Websites” – Jon Duckett
- W3Schools HTML y CSS: https://www.w3schools.com/html/ / https://www.w3schools.com/css/

**Objetivos:**
- Estructura HTML, etiquetas básicas, listas, imágenes
- Formularios simples
- Box model, layout y colores

**Tips & Tricks:**
- Usa **Chrome DevTools** para inspeccionar tu código
- Prueba colores con la herramienta online: https://colorhunt.co
- Mini-proyecto: crea tu **página personal** con tu info y fotos

**Práctica:** Crear una página con título, párrafos, listas y un formulario simple, estilizado con CSS.

---

### Semana 2: JavaScript básico
**Libros/documentos recomendados:**
- “Eloquent JavaScript” – Marijn Haverbeke
- “JavaScript & JQuery: Interactive Front-End Web Development” – Jon Duckett
- MDN JS: https://developer.mozilla.org/es/docs/Web/JavaScript

**Objetivos:**
- Variables, operadores, condicionales, loops
- Manipulación del DOM
- Eventos (`onclick`, `onchange`, `onload`)

**Tips & Tricks:**
- Practica en **CodePen** o **JSFiddle** para ver resultados en vivo
- Empieza siempre con **console.log()** para depurar
- Mini-proyecto: botón que cambie el color de un párrafo

**Práctica:** Crear una página interactiva con un botón que modifique texto o estilo dinámicamente.

---

### Semana 3: Introducción a Qlik Sense APIs
**Libros/documentos recomendados:**
- Qlik Sense Dev Hub: https://developer.qlik.com
- Capability API Docs: https://help.qlik.com/en-US/sense-developer/Subsystems/APIs/Content/Sense_API/Capability-API/Capability-API.htm
- “Learning Qlik Sense Data Visualization” – Christopher Ilacqua

**Objetivos:**
- Comprender Dev Hub, Hub, Engine y Capability API
- Conectar JS con Sense
- Leer tablas y mostrar datos en HTML

**Tips & Tricks:**
- Usa un **archivo JSON de prueba** para practicar antes de conectarte a Sense
- Mantén siempre un **log de errores en la consola**
- Mini-proyecto: mostrar tabla de Sense en HTML y filtrar por dimensión

---

### Semana 4: Primer Mashup
**Libros/documentos recomendados:**
- Qlik Mashups Docs: https://help.qlik.com/en-US/sense-developer/Subsystems/Hub/Content/Sense_Hub/Using-mashups.htm
- “Qlik Sense Extensions Cookbook” – Pablo Labbe

**Objetivos:**
- Crear carpeta de mashup en Dev Hub
- Incrustar gráficos (bar chart, KPI)
- Agregar filtros interactivos y estilizar con CSS

**Tips & Tricks:**
- Divide tu código JS en funciones para mantenerlo limpio
- Usa **Flexbox** para layout responsive
- Mini-proyecto: mashup funcional con un gráfico y filtro

---

## Mes 2: Extensiones y Mashups Avanzados

### Semana 5: Extensiones básicas
**Libros/documentos recomendados:**
- “Qlik Sense Extensions Cookbook” – Pablo Labbe
- Qlik Branch: https://branch.qlik.com

**Objetivos:**
- Estructura de extensión (`Definition`, `Script`, `Paint`)
- Crear KPI con color condicional
- Gráfico custom con JS/SVG

**Tips & Tricks:**
- Empieza con **KPI simple** antes de gráficos complejos
- Guarda versiones intermedias para no perder cambios
- Mini-proyecto: KPI dinámico con color condicional

---

### Semana 6: Interactividad y eventos
**Libros/documentos recomendados:**
- Enigma.js: https://github.com/qlik-oss/enigma.js
- Qlik Sense API Examples: https://developer.qlik.com/guides

**Objetivos:**
- Capturar selección de usuarios
- Conectar 2 visualizaciones (filtro afecta otra)
- Actualización de datos en tiempo real

**Tips & Tricks:**
- Practica con **datos de ejemplo** antes de tus apps reales
- Usa `console.log` para seguir flujo de eventos
- Mini-proyecto: mashup con 2 gráficos interactivos

---

### Semana 7: Integración con APIs externas
**Libros/documentos recomendados:**
- REST API Qlik Sense: https://help.qlik.com/en-US/sense-developer/Subsystems/Engine-API/Content/Sense_EngineAPI/REST-API/REST-API.htm

**Objetivos:**
- Conectar JSON externo a mashup
- Validar y manejar errores

**Tips & Tricks:**
- Prueba APIs con **Postman** antes de integrarlas
- Mini-proyecto: mashup con Sense + datos externos

---

### Semana 8: Optimización
**Libros/documentos recomendados:**
- CSS Flexbox Guide: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- Qlik Sense Best Practices: https://help.qlik.com

**Objetivos:**
- Modularizar código JS
- Diseño responsive
- Mejorar performance y logging

**Tips & Tricks:**
- Divide los mashups grandes en **módulos pequeños**
- Usa `setTimeout` o `requestAnimationFrame` para animaciones suaves

---

## Mes 3: Python + Qlik Sense y proyectos finales

### Semana 9: Python básico para Sense
**Libros/documentos recomendados:**
- “Python for Data Analysis” – Wes McKinney
- PyQlik: https://github.com/qlik-oss/pyqlik-engine
- Pandas Docs: https://pandas.pydata.org/

**Objetivos:**
- Conectar Python a Sense
- Leer y transformar datos en DataFrames
- Exportar resultados a CSV/QVD

**Tips & Tricks:**
- Usa **Jupyter Notebook** para pruebas interactivas
- Mini-proyecto: generar reporte Sense con Python

---

### Semana 10: Automatización
**Libros/documentos recomendados:**
- “Automate the Boring Stuff with Python” – Al Sweigart
- Python Requests: https://docs.python-requests.org/

**Objetivos:**
- Automatizar cargas QVD
- Actualizar mashups automáticamente
- Manejo de errores y logs

**Tips & Tricks:**
- Programa tus scripts con **task scheduler de Windows** para pruebas automáticas
- Mini-proyecto: script que actualice mashup y exporte reporte

---

### Semana 11-12: Proyectos finales
**Objetivos:**
- Proyecto 1: Mashup interactivo con 2 gráficos Sense + filtros + Python
- Proyecto 2: Extensión custom avanzada con métricas dinámicas y visualización interactiva

**Tips & Tricks:**
- Documenta tu código paso a paso
- Usa control de versiones (Git) para guardar avances

---

## Lista de Spotify para estudiar
- “Focus Flow” – Spotify playlist
- “Deep Focus” – Spotify playlist
- “Lo-Fi Beats” – Spotify playlist
- “Coding Mode” – Spotify playlist
- “Instrumental Study” – Spotify playlist

**Tip:** Mantén la música **sin letras** para evitar distracciones y ajusta volumen bajo-medio.

