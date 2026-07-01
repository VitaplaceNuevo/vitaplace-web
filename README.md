# Vitaplace — Prototipo Web

Sitio estático (HTML + CSS + JS, sin frameworks ni build step) para la clínica Vitaplace, Viña del Mar.

## Estructura

```
index.html                 → Página de inicio (home)
tratamientos-listado.html  → Listado de todos los tratamientos
```

## Editar el sitio

Todo el código (HTML, CSS y JS) está en un solo archivo por página — no hay proceso de build.
Puedes editar directamente el texto, colores (variables CSS en `:root`) o imágenes, y los cambios
se reflejan tal cual al recargar.

## Despliegue

Este proyecto está pensado para desplegarse como sitio estático en **Vercel**, conectado a este
repositorio de **GitHub**. Cualquier cambio que subas (`git push`) a la rama principal se publica
automáticamente en unos segundos.

No requiere configuración adicional (sin `vercel.json`, sin dependencias, sin build command).
