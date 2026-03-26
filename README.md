# Líneas de Investigación e Innovación Tecnológica — IDC 2026

Una plataforma web interactiva e infográfica diseñada para presentar la convocatoria, metodología y líneas de investigación del **Instituto de Educación Superior Público "Diseño & Comunicación" (IDC)** para el período 2026. 

Este proyecto digital traduce documentación académica compleja (criterios de innovación, presupuestos, metodologías ABPP y métricas ROI/ROAS) en una experiencia de usuario fluida, escaneable y visualmente atractiva, orientada a docentes, estudiantes y egresados de las especialidades de diseño y comunicación.

## 🚀 Características Principales

* **Arquitectura de Datos Dinámica:** El contenido principal (Líneas transversales, Presupuestos, Temas propuestos, Diagrama de Gantt) se genera dinámicamente mediante JavaScript a partir de objetos y arrays estructurados, facilitando la actualización de la información sin tener que reescribir el HTML.
* **Sistema de Navegación "Sticky" y Scroll Suave:** Menú de acceso rápido a las diferentes áreas de investigación (Interiores, Publicitario, Modas, Audiovisual) con un indicador de progreso de lectura.
* **Componentes UI Interactivos:** * Paneles laterales deslizables (Off-canvas) para detalles de las líneas de investigación.
    * Sistema de pestañas (Tabs) y acordeones anidados para explorar temas por carrera.
    * Diagrama de Gantt interactivo con tooltips dinámicos (posicionamiento inteligente en pantalla).
* **Gráficos Nativos:** Gráficos de barras y anillos (Donut charts) renderizados puramente con CSS y SVG, sin librerías externas pesadas.
* **Accesibilidad y UX:** Soporte para navegación por teclado, enlaces de "salto al contenido principal" para lectores de pantalla, y etiquetas `aria-*` implementadas.
* **Diseño Responsivo:** Adaptable a dispositivos móviles, tablets y escritorios mediante CSS Grid y Flexbox.

## 🛠️ Tecnologías Utilizadas

Este proyecto sigue una filosofía *Vanilla*, asegurando tiempos de carga ultrarrápidos y máxima compatibilidad:

* **HTML5:** Semántico y estructurado.
* **CSS3:** Uso avanzado de *Custom Properties* (variables CSS), animaciones `@keyframes`, funciones de color modernas (`color-mix`) y CSS Grid.
* **JavaScript (ES6+):** Manipulación del DOM, Intersection Observers para animaciones al hacer scroll, y renderizado funcional de datos.
* **Fuentes:** Google Fonts (*Nunito* para cuerpo de texto y *Playfair Display* para títulos).

## 📂 Estructura de Datos (Para desarrolladores/editores)

Si necesitas actualizar el contenido para futuros semestres, dirígete a la sección de scripts al final del archivo `index.html`. Encontrarás constantes de datos fácilmente editables:

* `areaData`: Contiene las áreas académicas, sus colores institucionales y líneas base.
* `criteriaData`: Criterios de innovación (Incremental, Disruptiva, Radical) e indicadores financieros (ROAS, CAC, LTV) por carrera.
* `ganttData`: Controla los hitos del cronograma institucional (10 meses).
* `ltData` & `themesData`: Repositorio de los temas de investigación transversales y por área.
* `bexpData`: Desglose del capital semilla y presupuesto piloto.

## ⚙️ Instalación y Despliegue

1. Clona este repositorio o descarga los archivos fuente.
2. Asegúrate de tener el archivo del logo institucional (`Logo_IDC.jpg` y `Logo_IDC_tras.png`) en el mismo directorio raíz que el `index.html`.
3. Abre `index.html` en cualquier navegador web moderno. ¡No requiere servidor local ni proceso de compilación (build)!
4. **Para despliegue:** Puedes alojar este proyecto fácilmente y de forma gratuita en plataformas como **GitHub Pages**, **Vercel** o **Netlify** subiendo directamente la carpeta.

## 👨‍🏫 Autoría y Créditos

Proyecto desarrollado y dirigido por el **Mg. Mario Rafael Quiroz Martínez** para la Unidad de Investigación del Instituto IDC. El diseño de esta plataforma refleja un alto rigor académico, combinando estándares de experiencia de usuario (UX) con metodologías de educación superior orientadas al Aprendizaje Basado en Proyectos Productivos (ABPP).

---
*Documento generado para la Unidad de Investigación IDC - 2026.*