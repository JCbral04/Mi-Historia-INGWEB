# Mi Historia - El Viaje del Código

Un sitio web interactivo y moderno que narra el viaje de aprendizaje en desarrollo web, desde la curiosidad inicial hasta la creación de experiencias digitales.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

##  Descripción

Este proyecto es una narrativa interactiva que documenta el proceso de aprendizaje de desarrollo web. A través de una experiencia visual inmersiva, el usuario puede explorar:

- **El Descubrimiento**: Cómo comenzó el interés por el código
- **El Aprendizaje**: Cronología de habilidades adquiridas (HTML, CSS, JavaScript)
- **La Creación**: Aplicación práctica del conocimiento en proyectos reales
- **La Reflexión**: Lecciones aprendidas durante el proceso

##  Características

###  Diseño y Experiencia de Usuario
- **Diseño Responsive**: Adaptable a cualquier dispositivo (mobile-first)
- **Modo Oscuro/Claro**: Cambio de tema con persistencia en localStorage
- **Animaciones Suaves**: Efectos de scroll, transiciones y micro-interacciones
- **Canvas Interactivo**: Fondo animado con partículas y conexiones dinámicas
- **Efecto Typewriter**: Texto dinámico que simula escritura en la página de inicio

###  Funcionalidades JavaScript
- **Scroll Reveal**: Animaciones al hacer scroll usando Intersection Observer API
- **Demo Interactiva**: Controles en tiempo real para modificar propiedades CSS (color, borde, rotación)
- **Navegación Suave**: Scroll animado entre secciones
- **Efecto Navbar**: Cambio de apariencia del navbar al hacer scroll
- **Modal de Características**: Ventana modal con lista de tecnologías implementadas

##  Estructura del Proyecto

```
Mi historia/
├── index.html          # Estructura principal del sitio
├── styles.css          # Estilos personalizados y componentes
├── script.js           # Lógica interactiva y animaciones
└── README.md           # Documentación del proyecto
```

##  Archivos

### `index.html`
Documento HTML5 semántico que contiene:
- Navegación fija con enlaces a secciones
- 5 secciones principales: Inicio, Descubrimiento, Aprendizaje, Proyecto, Reflexión
- Timeline interactivo mostrando el progreso de aprendizaje
- Demo interactiva con controles de manipulación DOM
- Modal de características implementadas
- Footer con información del proyecto

### `styles.css`
Hoja de estilos con:
- Variables CSS para theming (claro/oscuro)
- Clases utilitarias personalizadas
- Animaciones keyframes (float, gradient, pulse)
- Componentes: tarjetas, timeline, botones, playground
- Efectos visuales: glassmorphism, glow, sombras
- Estilos responsive con media queries

### `script.js`
Lógica de la aplicación incluyendo:
- **Gestión de Tema**: Alternancia entre modo oscuro/claro
- **Typewriter Effect**: Animación de texto ciclando palabras
- **ScrollReveal**: Animaciones de entrada al scroll
- **Canvas Animation**: Sistema de partículas interactivas
- **Demo Controls**: Funciones para manipular el DOM (`changeColor`, `changeRadius`, `changeRotate`)
- **Modal Management**: Apertura/cierre de modales
- **Smooth Scroll**: Navegación fluida entre secciones

##  Tecnologías Utilizadas

| Tecnología | Propósito |
|------------|-----------|
| HTML5 Semántico | Estructura accesible y SEO-friendly |
| CSS3 | Estilos modernos con Flexbox y Grid |
| Tailwind CSS | Framework CSS utility-first (vía CDN) |
| JavaScript Vanilla | Interactividad sin dependencias externas |
| Canvas API | Animaciones de partículas en el fondo |
| Intersection Observer API | Detección eficiente de elementos en viewport |
| LocalStorage API | Persistencia de preferencias de tema |

##  Componentes Destacados

### 1. Timeline de Aprendizaje
Visualización cronológica del progreso:
- Semana 1-2: HTML5 y estructura semántica
- Semana 3-4: CSS3, Flexbox y Grid Layout
- Semana 5-6: JavaScript, DOM y eventos

### 2. Playground Interactivo
Sección demo donde el usuario puede:
- Cambiar colores de fondo
- Ajustar radio de borde
- Modificar rotación del elemento

Todo en tiempo real mediante manipulación del DOM.

### 3. Sistema de Partículas
Fondo animado con:
- 100 partículas máximo (adaptativo al ancho de pantalla)
- Conexiones entre partículas cercanas
- Adaptación de colores según el tema

##  Compatibilidad

- **Navegadores**: Chrome, Firefox, Safari, Edge (últimas versiones)
- **Dispositivos**: Desktop, tablet, mobile
- **Resoluciones**: Desde 320px hasta ultra-wide

##  Cómo Usar

1. Clona o descarga el repositorio
2. Abre `index.html` en tu navegador
3. Explora las diferentes secciones haciendo scroll
4. Prueba los controles interactivos en la sección "Demo Interactiva"
5. Cambia entre modo oscuro y claro usando el botón en la navbar

##  Aprendizajes Documentados

El proyecto refleja los siguientes aprendizajes clave:

- **Paciencia**: Cada error es una oportunidad de aprendizaje
- **Creatividad**: La combinación de diseño y lógica crea experiencias únicas
- **Comunidad**: La documentación y recursos colaborativos son fundamentales

##  Autor

**AU** - Proyecto de Desarrollo Web 2026

