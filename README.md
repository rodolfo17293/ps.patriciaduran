# Patricia Durán — Psicóloga

Landing page premium, minimalista y mobile-first para la psicóloga Patricia Durán.

Página única autocontenida en HTML/CSS/JS, con copy en español.

## Estructura

- **`Patricia Durán - Psicóloga.html`** — la landing completa (estilos y scripts embebidos).
- **`assets/`** — recursos del sitio:
  - `hero.png` — póster/fallback del hero y apoyo visual de la sección de precios.
  - `transition.mp4` — video de fondo del hero (loop ping‑pong, muted, autoplay).

## Características

- **Hero** con video en *ping‑pong loop* (avanza y retrocede sin corte) y velo crema para legibilidad.
- **Ondas de sonido** animadas como separadores entre secciones.
- **Corazón que se une al scroll**: dos mitades en SVG que se acercan y se unen con un glow de confirmación.
- *Reveals* suaves al entrar en viewport, navbar sticky con blur y menú móvil.
- Paleta pastel (Fraunces + Inter), grano sutil y glows difusos.
- SEO/OpenGraph, encabezados semánticos, `alt` en imágenes, foco visible y `prefers-reduced-motion` respetado.
- Mobile-first y totalmente responsive.

## Uso

Abre el archivo HTML en un navegador, o sírvelo con cualquier servidor estático:

```sh
python3 -m http.server
```

## Notas

- `image2.png` no venía en el brief original; la sección de precios usa un encuadre de la textura de marca (`hero.png`).
- Precios y datos de contacto (email, teléfono, dirección) son **placeholders** pendientes de los datos reales.
