# renamr

Renombrador masivo de imágenes. Todo client-side, sin backend.

## Stack

- [Astro](https://astro.build/) — framework estático
- [JSZip](https://stuk.github.io/jszip/) — generación del .zip en el navegador
- Vanilla JS — lógica de interacción
- Google Fonts — Syne + DM Mono + DM Sans

## Setup local

```bash
npm install
npm run dev
```

Abre en http://localhost:4321

## Deploy en Vercel

1. Subí el proyecto a un repositorio en GitHub
2. Importalo desde [vercel.com](https://vercel.com)
3. Vercel detecta Astro automáticamente — no necesita configuración extra
4. Listo ✓

## Funcionalidades

- Drag & drop o selección múltiple de imágenes (JPG, PNG, WEBP, GIF)
- Límite configurable (por defecto: 100 imágenes)
- Nombre semilla + numeración automática con padding de dígitos
- Vista previa del nombre generado en tiempo real
- Thumbnails de las primeras 20 imágenes
- Descarga de todas las imágenes renombradas en un .zip
- 100% privado: ninguna imagen sale del navegador del usuario
