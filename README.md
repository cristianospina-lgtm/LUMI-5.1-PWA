# LUMI 5.1 PWA - Instalación restaurada

Este paquete restaura el control de instalación en la pantalla de bienvenida.

## Archivos incluidos
- `index.html`: botón de instalación, evento `beforeinstallprompt`, detección de instalación y guía manual para Android/iOS.
- `manifest.json`: metadatos e iconos de la PWA.
- `sw.js`: caché versionada del portal estático.
- `logo-lumi.png`: mascota principal.
- `icons/icon-192.png` y `icons/icon-512.png`: iconos de instalación.

## Publicación
Sube y reemplaza los archivos en la raíz del repositorio `LUMI-5.1-PWA`.
Mantén los dos iconos dentro de la carpeta `icons`.

## Notas
Chrome solo emite `beforeinstallprompt` cuando considera que se cumplen sus criterios de instalación.
Si el evento no se emite, el botón muestra instrucciones alternativas del navegador.
En iPhone/iPad, la instalación se realiza desde Safari > Compartir > Agregar a pantalla de inicio.

La aplicación principal sigue alojada en Google Apps Script. Este paquete no modifica backend,
autenticación, permisos, hojas de cálculo ni módulos.
