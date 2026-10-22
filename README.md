# Portadas del blog de actuaria.com en WebP

Copias livianas de las portadas de los artículos del blog (campo `main-image` de la colección Blog Posts de Webflow),
convertidas el 2026-10-22: WebP calidad 80, como máximo 1200 px de ancho, misma proporción que el original, sin
metadatos.

Este repositorio sirve solo de **punto de paso**: Webflow descarga cada archivo desde aquí cuando se cambia la portada
del artículo por la API, y lo guarda en su propio CDN. El sitio no carga nada desde este repositorio.

Los nombres son el `fileId` de la portada original en Webflow. El detalle (archivo original, peso y medidas antes y
después) está en `conversion.json`.
