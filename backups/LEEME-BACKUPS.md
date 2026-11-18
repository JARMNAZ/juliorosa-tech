# Historial de Versiones (Backups del Portafolio)

En esta carpeta se guardan automáticamente todas las versiones anteriores de `index.html` antes de cada despliegue a producción:

1. **`v1-portafolio-original.html`** — Versión inicial del portafolio estático original.
2. **`v2-portafolio-linkedin-actualizado.html`** — Versión con actualización del enlace de LinkedIn (`julio-rosa-tech`).
3. **`v3-hub-instagram-y-casos-base.html`** — Versión con el Hub de Documentación de Instagram (`@juliorosa.tech`), menús desplegables, actualización de CV 2026 y tarjetas de Casos de Estudio (antes de cargar videos/capturas).
4. **`v4-produccion-noc-y-sitting-multimedia.html`** — Versión con los Casos de Estudio interactivos completos (**Sitting Digital para Bodas** + **Mesa de Servicio NOC**), antes de la adaptación integral para celulares.
5. **`v5-produccion-mobile-responsive.html`** — Versión optimizada tanto para PC como para celulares (Mobile-First responsive, barra superior compacta en 2 filas, cintas táctiles deslizables en casos de estudio y cuadrícula simétrica de botones).
6. **`v6-produccion-autodm-n8n.html`** — Versión con el Caso de Estudio completo de Auto-DM Instagram (n8n + Graph API + Telegram SRE), antes de cargar la documentación multimedia de Merchant Integration Workflow - Fintech.

## ¿Cómo restaurar una versión anterior?
Simplemente copia cualquiera de los archivos `.html` de esta carpeta, renómbralo a `index.html` en la raíz del proyecto (`C:\Users\julio\Desktop\Deploy-web-porfafolio-jr\index.html`) y haz `git commit` + `git push`.
