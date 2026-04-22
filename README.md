# Renamify

Renombrador masivo de imágenes. Todo client-side, sin backend.

## Stack

- [Astro](https://astro.build/) — framework estático
- [JSZip](https://stuk.github.io/jszip/) — generación del .zip en el navegador
- Vanilla JS — lógica de interacción
- Google Fonts — Space Grotesk + DM Mono + DM Sans

## Setup local

\```bash
npm install
npm run dev
\```

Abre en http://localhost:4321

## Deploy en Vercel

1. Subí el proyecto a un repositorio en GitHub
2. Importalo desde [vercel.com](https://vercel.com)
3. Vercel detecta Astro automáticamente — sin configuración extra
4. Listo ✓

## Funcionalidades

- Drag & drop o selección múltiple (JPG, PNG, WEBP, GIF)
- Hasta 400 imágenes por vez
- Nombre semilla + separador configurable (`_`, `-`, o ninguno)
- Numeración automática con dígitos y número de inicio configurables
- Reordenar imágenes con drag & drop
- Eliminar imágenes individuales antes de descargar
- Vista previa del nombre generado en tiempo real
- Historial de nombres recientes
- Exportar .zip solo, con mapeo.csv, o con mapeo.json
- Modo claro/oscuro
- 100% privado: ninguna imagen sale del navegador