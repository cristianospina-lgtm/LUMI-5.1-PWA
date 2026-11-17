# LUMI 5.1 PWA

Portal instalable para acceder a LUMI 5.1.

## Aplicación principal
https://script.google.com/macros/s/AKfycbxfUMAqVuXjSMEbpO5zbEW5ZQ74oG9RB3yPIls2tMN_a77g0mlkil_3ULfRc1X7cKsiOw/exec

## Publicar en GitHub Pages
1. Subir todos los archivos y carpetas de este paquete a la raíz del repositorio `LUMI-5.1-PWA`.
2. Abrir Settings > Pages.
3. En Build and deployment, elegir `Deploy from a branch`.
4. Seleccionar `main` y `/(root)`.
5. Guardar y esperar la publicación.

## Importante
GitHub Pages aloja únicamente el portal PWA. La aplicación, autenticación,
permisos y datos continúan en Google Apps Script. Se requiere conexión a
Internet para abrir la aplicación principal. El service worker solo cachea
los archivos estáticos del portal; no almacena información personal ni clínica.
