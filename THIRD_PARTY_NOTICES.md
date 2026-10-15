# Third-party mapping libraries and tools

The application ships its own dependencies at the repository root. The hosted page does not require external CDNs or commercial map tiles.

- **OpenLayers:** `ol.js`, `ol.css` — OpenLayers v10.7.0, BSD-2-Clause; https://github.com/openlayers/openlayers
- **Proj4js:** `proj4.js` — Proj4js v2.5.0, MIT; https://github.com/proj4js/proj4js
- **Data workflow:** OpenStreetMap data via QuickOSM/QGIS and qgis2web, with subsequent customized OpenLayers code.

Each third-party component remains subject to its own licence. The OpenStreetMap database licence is addressed in `DATA_LICENSE.md`.
