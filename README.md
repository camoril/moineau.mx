# MOINEAU.mx

Landing page minimalista para MOINEAU (estudio de arte y joyeria).

## Estado

Proyecto activo con una sola pagina estatica (`index.html`) y enfoque editorial/minimal.

## Caracteristicas

- Hero centrado con logo principal.
- Texto manifiesto bilingue (ES/EN).
- Idioma por defecto en ingles.
- Boton para alternar idioma.
- Boton para alternar tema (`dark` / `light`) con persistencia en `localStorage`.
- Interaccion de revelado de texto mediante flecha (mobile y desktop).
- Iconos de contacto (correo e Instagram).
- Favicon generado desde el logo en version blanca.
- Ajustes responsive y atributos ARIA para accesibilidad basica.

## Estructura

- `index.html`: pagina principal (HTML, CSS y JS en un solo archivo).
- `logo*.svg`: variantes de logo usadas en distintas vistas.
- `intrepid.ttf`: tipografia local del proyecto.
- `favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png`, `favicon.png`: favicon del sitio.

## Desarrollo local

Desde la carpeta del proyecto:

```bash
python3 -m http.server 8000
```

Abrir en navegador:

- `http://localhost:8000`

## Deploy

Sitio estatico apto para GitHub Pages, Netlify, Vercel (modo estatico) o cualquier hosting HTML.

## Notas

- El repositorio no usa build step.
- Para cambios rapidos, editar directamente `index.html`.
- Si se actualiza branding (logos/fuentes), mantener consistencia entre tema claro/oscuro y favicon.
