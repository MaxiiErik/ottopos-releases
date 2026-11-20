# OttoPOS — instaladores

Este repositorio contiene **solo los instaladores y paquetes de actualización** de OttoPOS (archivos de Velopack), publicados como *releases*. No contiene código fuente.

- Cada release `vX.Y.Z` trae el paquete `OttoPOS-X.Y.Z-full.nupkg`, el instalador `OttoPOS-win-Setup.exe` y `version-publicada.json` (versión, SHA-256 y tamaño del paquete).
- Las cajas descargan las actualizaciones desde acá, pero solo instalan un paquete si su SHA-256 coincide con el que firma el servidor de licencias: un archivo cambiado acá se rechaza.
- Los releases marcados como *pre-release* son del canal de prueba.
