# La Braza Dorada — Landing Page Prototype

Landing page de prototipo para un restaurante/parrilla ficticio, pensada como pieza de portafolio para ofrecer servicios de desarrollo web. Sin dependencias ni build step: HTML, CSS y JS puros.

## 🔗 Ver la página en vivo

**https://malvarezdam.github.io/Landing-Page-Test/**

## Contenido

- Hero con llamado a la acción
- Sección "Nosotros"
- Menú con categorías (Entradas, Platos Fuertes, Postres, Bebidas)
- Galería
- Testimonios de clientes
- Ubicación con mapa y horarios
- Redes sociales
- Formulario de contacto
- Botón flotante de WhatsApp

## Estructura

```
index.html
css/style.css
js/script.js
```

## Deploy

El sitio se publica automáticamente en GitHub Pages mediante el workflow `.github/workflows/deploy-pages.yml` cada vez que se hace push a la rama `claude/restaurant-landing-prototype-lyaej7`.

> Nota: la primera vez que se activa GitHub Pages en un repositorio, GitHub exige habilitarlo manualmente una única vez (no se puede automatizar por seguridad): **Settings → Pages → Build and deployment → Source: "GitHub Actions"**. Una vez hecho ese paso, todos los despliegues siguientes son 100% automáticos.
