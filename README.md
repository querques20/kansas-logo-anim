# Animación del logo de Kansas

Animación del logotipo de Kansas en una sola página HTML. El texto se convierte en trazos SVG con opentype.js y se dibuja con GSAP, como si se escribiera a mano.

## Cómo funciona

- Carga una tipografía caligráfica con opentype.js y convierte el texto en trazos (`path`) de SVG.
- Si una fuente no carga, prueba con la siguiente: Cinzel Decorative, Corinthia y Great Vibes.
- GSAP anima el trazo para el efecto de dibujo.

## Cómo verlo

Abrí `kansas-logo.html` en el navegador. Necesita conexión a internet, porque las fuentes y las librerías se cargan desde CDN.

## Stack

HTML, CSS, SVG, opentype.js y GSAP.
