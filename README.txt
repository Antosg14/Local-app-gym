RUTINA ULUL - MINI APP PWA

ARCHIVOS
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

IMPORTANTE
Para que funcione como una PWA real, incluyendo modo offline y "Agregar a pantalla de inicio",
debe publicarse mediante HTTPS. Abrir index.html directamente desde Archivos de iPhone no basta
para registrar el Service Worker.

FORMA RÁPIDA DE PUBLICAR
1. Descomprime esta carpeta.
2. Súbela a un hosting estático como GitHub Pages, Netlify o Cloudflare Pages.
3. Abre la URL HTTPS resultante en Safari del iPhone.
4. Pulsa Compartir.
5. Pulsa "Agregar a pantalla de inicio".
6. La app aparecerá como ULUL y conservará pesos, repeticiones y progreso en el dispositivo.

FUNCIONES
- Upper A / Lower A / Recuperación / Upper B / Lower B
- contador +/- de repeticiones
- registro de reps y peso por serie
- check de series
- progreso del entrenamiento
- temporizador 90 s / 2 min / 3 min
- almacenamiento local
- exportación del resumen
- funcionamiento offline después de la primera carga, una vez alojada por HTTPS
