# Red Ferroviaria de España — Visor Interactivo

Mapa interactivo con **2.187 estaciones** y **387 líneas** de la red ferroviaria española, incluyendo AVE, Cercanías, Rodalies, FEVE, Media Distancia y más.

## 🌐 Visor online

[https://andermr2-ui.github.io/red-ferroviaria-espana/](https://andermr2-ui.github.io/red-ferroviaria-espana/)

## 🗺️ Funcionalidades

- Mapa interactivo con OpenStreetMap + Leaflet.js
- Filtro por tipo de línea (AVE, Cercanías, Rodalies, FEVE, etc.)
- Búsqueda por nombre o ID de línea
- Popups con información de cada estación
- Leyenda dinámica de tipos mostrados

## 📂 Estructura

```
docs/                  → GitHub Pages (visor web)
├── index.html         → Visor principal
├── estaciones.geojson → 2.187 estaciones con coordenadas
├── lineas.geojson     → 387 líneas
└── lineas/            → GeoJSON individual por línea
visor/                 → Copia local del visor
```

## 🛠️ Origen de datos

Base de datos ferroviaria curada manualmente desde OpenStreetMap, Wikipedia y OpenRailwayMap, con coordenadas verificadas y provincias corregidas.
