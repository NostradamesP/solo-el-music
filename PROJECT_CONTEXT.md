# Solo el Music — Sitio Web Profesional

## Stack
- **HTML5** semántico
- **CSS3** puro (custom properties, animaciones, grid, flexbox, SVG filters)
- **JavaScript** vanilla (Canvas API, Intersection Observer, animaciones)
- **GSAP 3.12.5** — animaciones scroll-driven (ScrollTrigger)
- **Lenis 1.1.4** — smooth scrolling
- **Plyr 3.7.8** — reproductor de video

## Estructura
```
solo-el-music/
├── index.html             # Página principal (single-page)
└── PROJECT_CONTEXT.md     # Este archivo
```

## Descripción
Sitio web profesional para **Solo el Music**, un productor musical y creador de contenido en YouTube (desde 2011). Ofrece servicios de:
- Producción musical
- Beats personalizados
- Mezcla profesional
- Mastering
- Edición vocal
- Tutoriales y clases

## Diseño — Inspirado en Sonar Music (sonarmusic.com.au)
El diseño sigue la estética de Sonar Music:
- **Fondo oscuro** `#1D1D1B` con acentos en `#efefeb` (blanco cálido)
- **Tipografía editorial** — Inter, pesos 300-800, sans-serif limpia
- **Grid de 3 columnas** como impacto visual principal (hero alternativo)
- **Barras de ecualizador** (sound lines) como firma visual — animadas con CSS
- **Modal QuickView** tipo Sonar para previsualizar proyectos
- **Marquee** con texto en escala para profundidad
- **Loading screen** con líneas pulsantes
- **Sistema de modo** con navbar transparente que cambia al scrollear
- **Máscara SVG** en tarjetas (`mask`) para bordes suaves
- **Líneas punteadas** como detalle decorativo (dashed borders)
- **GSAP ScrollTrigger** para animaciones al hacer scroll

## Secciones
1. **Loading overlay** — 10 líneas verticales animadas
2. **Navbar** — transparente, minmal, con efecto blur al scrollear
3. **Hero** — tipográfico, con gradientes de fondo sutiles
4. **Three-column grid** — 6 proyectos en cuadrícula de 3 columnas
5. **Sound section** — barras de ecualizador + about text
6. **Services** — grid de 3×2 con dashed borders
7. **YouTube** — 6 cards con play overlay, link al canal
8. **Marquee** — texto horizontal infinito "SOLO EL MUSIC — BEATS — ..."
9. **Stats** — 4 columnas con números animados
10. **Contact** — formulario + métodos de contacto
11. **Footer** — con mini ecualizador y redes sociales

## Canal de YouTube
- URL: https://www.youtube.com/channel/UCJ5PtSmguS49eUv3JoZmSXA
- Subscriptores: ~165
- Videos: 25+
- Vistas totales: 87.6K+
- Contenido: Tutoriales de producción musical en español (alta calidad)

## Comandos
- Abrir en navegador: `open index.html`
- No requiere build — solo abrir en navegador moderno
