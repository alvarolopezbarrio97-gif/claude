# Selección de herramientas — SEO y diseño web

Documento de trabajo para cerrar el stack que usaré en el proyecto del
cliente caucho (y como base reutilizable para futuros encargos de dWolf).
Se cerrará de la mano con Claude.

## Criterios de decisión

- **Rendimiento** (Core Web Vitals, tiempo de carga real).
- **Salud SEO técnica** (crawl, indexación, schema, internacionalización).
- **Coste** (licencias mensuales / anuales, coste por proyecto).
- **Curva de aprendizaje** y productividad.
- **Compatibilidad** con lo que usa dWolf (WordPress + builder confirmado).

## SEO — shortlist a evaluar

### Análisis y estrategia
- **Ahrefs** — backlinks, keywords, auditoría.
- **Semrush** — alternativa / complemento a Ahrefs.
- **Sistrix** — visibilidad, buena para mercado ES.

### Auditoría técnica
- **Screaming Frog SEO Spider** — crawl de referencia.
- **Google Search Console** — obligatorio, datos reales de Google.
- **Google Analytics 4** — medición.
- **Looker Studio** — informes al cliente.

### Velocidad y Core Web Vitals
- **PageSpeed Insights / Lighthouse**.
- **WebPageTest**.

### Contenido / IA
- Por decidir (asistentes para briefs, clusters, redacción asistida).

## Diseño y desarrollo web — shortlist a evaluar

### CMS / base
- **WordPress** (alineado con dWolf) vs. alternativas (Astro, framework
  headless) — decisión condicionada por lo que hoy usa dWolf.

### Page builder
- Candidato oficial de dWolf: *pendiente de confirmar* (sospecha: Cwicly).
- Alternativas a valorar si lo decido yo:
  - **Bricks Builder** — rendimiento alto, control CSS fino.
  - **Breakdance** — buena productividad.
  - **Cwicly** — cercano a Gutenberg nativo.

### Hosting
- Hosting gestionado orientado a rendimiento (a decidir).

### Librerías / optimización
- Plugin de caché y optimización (WP Rocket, LiteSpeed Cache…).
- Optimización de imágenes (AVIF/WebP, lazy loading).
- Plugin SEO (Rank Math / Yoast).

## Decisiones pendientes

- [ ] Confirmar builder usado por dWolf.
- [ ] Elegir 1 suite principal de SEO (Ahrefs vs Semrush vs combinación).
- [ ] Elegir builder propio para proyectos en los que yo controle la web.
- [ ] Definir plantilla de informe mensual SEO (Looker Studio).
