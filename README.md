# Proyecto PWA - Web del Hospital

Este proyecto es una aplicación web progresiva (PWA) desarrollada en React, con el objetivo de implementar funcionalidades offline y mejorar la experiencia de usuario en la web del hospital.

## Características
- Implementación de un **Service Worker** para funcionalidad offline.
- Creación de un **archivo de manifiesto** para la PWA.
- Estrategias de **almacenamiento en caché** como Cache-first y Stale-While-Revalidate.
- Validación con **Lighthouse** para asegurar el rendimiento y cumplimiento de estándares PWA.

## Estructura del Proyecto
```
public/
  └── manifest.json
src/
  ├── App.js
  ├── index.js
  └── service-worker.js
```

## Funcionalidades PWA
- **Manifiesto:** Configurado con nombre, iconos, color de fondo y modo standalone.
- **Service Worker:** Registra, precachea archivos esenciales y permite navegación offline.
- **Estrategia de Caché:** Implementadas estrategias Cache-first y Stale-While-Revalidate.

## Validación con Lighthouse
1. Abre la aplicación en el navegador (http://localhost:3000).
2. Abre las herramientas de desarrollo (F12) y selecciona la pestaña **Lighthouse**.
3. Genera el reporte y verifica el cumplimiento como PWA.

## Autor
- Criss

