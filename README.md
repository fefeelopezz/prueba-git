# Black Powers — Hamburguesas Artesanales

Sitio web estático de **Black Powers**, una hamburguesería de smash burgers artesanales en Hurlingham, Buenos Aires.

## Páginas

| Página | Archivo | Contenido |
|--------|---------|-----------|
| Inicio | `index.html` | Presentación, las más elegidas y ubicación |
| Menú | `pages/menu.html` | Carta completa de hamburguesas |
| Promos | `pages/promos.html` | Promociones vigentes |
| Pedidos | `pages/pedidos.html` | Cómo hacer un pedido (WhatsApp) y preguntas frecuentes |
| Contacto | `pages/contacto.html` | WhatsApp, Instagram, teléfono y ubicación |

## Tecnologías

- HTML5
- [Sass](https://sass-lang.com/) (SCSS), compilado a `css/main.css`
- [Bootstrap 5.3](https://getbootstrap.com/) vía CDN (navbar y acordeón)
- Google Fonts: Playfair Display y Plus Jakarta Sans

## Estructura

```
├── index.html
├── pages/          # Resto de las páginas
├── assets/img/     # Imágenes, logo y favicon
├── css/            # CSS compilado (no editar a mano)
└── scss/
    ├── main.scss   # Punto de entrada
    ├── base/       # Estilos generales
    ├── components/ # Navbar, acordeón, footer, etc.
    ├── pages/      # Estilos por página
    └── utilites/   # Variables, mixins y extends
```

## Cómo verlo

No necesita instalación: abrí `index.html` en el navegador (o usá Live Server en VS Code).

## Editar estilos

Los estilos se escriben en `scss/` y se compilan a `css/main.css`. Podés usar la extensión Live Sass Compiler de VS Code o compilar a mano:

```bash
npx sass --watch scss/main.scss css/main.css
```

Los colores y fuentes del sitio están en `scss/utilites/_variables.scss`.

## Contacto

- Instagram: [@black.powers_](https://www.instagram.com/black.powers_/)
