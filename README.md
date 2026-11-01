# Vereda data

Public data for the Vereda hiking app (Madeira and Porto Santo). The app's code lives in a separate
repository; this one only holds what the app downloads, so it can stay public:

- **Trail status:** the `status` branch holds `status.json`, the official open/closed list read twice
  a day (09:00 and 14:00 Madeira time). The app treats status older than 24 hours as unknown.
- **Offline map:** the release `maps-latest` holds `manifest.json`, which points to the map package on a
  `maps-YYYY.MM.DD` release (base map, contours, terrain as PMTiles).
- **Privacy policy:** `privacy/` (English and Portuguese), published with GitHub Pages for the
  Google Play listing.

Everything here is published by the app repository's GitHub Actions. Please don't edit it by hand.

## Licences

- Map data © OpenStreetMap contributors, ODbL 1.0. Tiles built with Planetiler (OpenMapTiles schema).
- Terrain © DROTe, Região Autónoma da Madeira (10 m terrain model, CC BY 4.0).
- Trail status from visitmadeira.com.

Vereda is an independent app. It is not made by, or linked to, the Regional Government of Madeira,
IFCN, Visit Madeira or IPMA.

Contact: 4vereda.app@gmail.com
