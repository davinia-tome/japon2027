# Japón 2027

Web del viaje a Japón (julio 2027), publicada con GitHub Pages.

- **`index.html`** — web (Tailwind + Leaflet). Mapa interactivo con los lugares por categoría + listado por ciudad con filtros.
- **`japan-trip.geojson`** — datos de los puntos (fuente única). Cada punto lleva `name`, `category`, `city`, `area`, `notes`, `hours`, `url`, `priority` y estilo (`marker-color`, `marker-symbol`).

## Actualizar

El máster de los datos vive en el workspace de Kiro
(`~/kiro-workspace/data/japan-trip/japan-trip.geojson`). Al añadir puntos nuevos se
copia aquí y se hace push; la web se regenera sola al cargar el GeoJSON.

## Categorías

🍜 restaurante · 🛏️ alojamiento · 🏛️ museo · 🛍️ tienda · ⭐ actividad · 🚆 transporte · ⛩️ visita

Pendiente: itinerario día a día (cuando se organicen las rutas por zonas).
