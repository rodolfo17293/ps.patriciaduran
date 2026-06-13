# Patricia Durán — Psicóloga

Landing page premium, minimalista y mobile-first para la psicóloga Patricia Durán.

Página única autocontenida en HTML/CSS/JS, con copy en español.

## Estructura

- **`index.html`** — la landing servida desde la raíz (GitHub Pages).
- **`Patricia Durán - Psicóloga.html`** — copia con el mismo contenido (archivo original del diseño).
- **`assets/`** — recursos del sitio:
  - `hero.png` — imagen de fondo del hero (textura de ondas) y apoyo visual de la sección de precios.
  - `patricia.png` — retrato de Patricia en el hero.
  - `transition.mp4` — video original del hero. **Actualmente sin uso** (el hero pasó a imagen estática); se conserva por si se quiere recuperar.

## Características

- **Hero** con imagen estática de fondo, velo crema para legibilidad y retrato de Patricia junto al titular.
- **Ondas de sonido** animadas como separadores entre secciones.
- **Corazón que se une al scroll**: dos mitades en SVG que se acercan y se unen con un glow de confirmación.
- **Planes**: sesión individual + packs de 4 y 8 sesiones.
- CTAs que abren **WhatsApp** con mensaje pre-escrito.
- *Reveals* suaves al entrar en viewport, navbar sticky con blur y menú móvil.
- Paleta pastel (Fraunces + Inter), grano sutil y glows difusos.
- SEO/OpenGraph, encabezados semánticos, `alt` en imágenes, foco visible y `prefers-reduced-motion` respetado.
- Mobile-first y totalmente responsive.

## Uso

Abre el archivo HTML en un navegador, o sírvelo con cualquier servidor estático:

```sh
python3 -m http.server
```

> Las dos páginas HTML deben mantenerse en sincronía: al editar `Patricia Durán - Psicóloga.html`, copia el resultado a `index.html`.

## Notas

- Algunos datos siguen como **placeholder** pendientes de confirmación: dirección (Providencia, Santiago), horario y los enlaces legales del footer.
</content>
</invoke>
