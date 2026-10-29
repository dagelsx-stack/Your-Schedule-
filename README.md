# Your Schedule · Inno-Vsion

App de horario instalable (PWA). Todo funciona con estos archivos, sin servidor propio.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub (por ejemplo `horario`) y sube **todo el contenido de esta carpeta** a la raíz (incluido `.nojekyll`).
2. En el repositorio: Settings -> Pages -> Source: "Deploy from a branch" -> rama `main`, carpeta `/ (root)` -> Save.
3. En un minuto tendrás la dirección `https://TU-USUARIO.github.io/horario/`.

## Instalar en el teléfono
Abre esa dirección en Chrome y elige "Instalar app" (o "Añadir a pantalla de inicio"). Se abre sin barra del navegador y, después de la primera carga con internet, funciona sin conexión.

## Convertir a APK
Con la app ya publicada, entra a https://www.pwabuilder.com, pega la dirección y descarga el paquete Android. Para instalarlo fuera de la tienda, permite "instalar apps desconocidas".

## Importante para no perder datos
- Abre siempre la app desde la misma dirección: los datos se guardan por dirección.
- Usa Ajustes -> Exportar horario de vez en cuando (la app te lo recuerda cada 30 días).

## Qué editar
- Nombre de la app: `name` y `short_name` en `manifest.webmanifest` (hoy "Your Schedule").
- Al publicar un cambio grande, sube el número de `VERSION` en `sw.js` para que los teléfonos actualicen.
