# Amsterdam Oost - Linnaeusstraat GIS Map

Interactive map of 45 food, drink, and shop locations along Linnaeusstraat and surrounding streets in Amsterdam Oost. Created for UvA Complex Systems for Policy — Challenge Based Project 2, Week 1.

## Files

| File | Description |
|------|-------------|
| `map.html` | Interactive web map — open in any browser, no server needed |
| `locations.geojson` | GeoJSON data (45 features) — works in QGIS, ArcGIS, Mapbox, etc. |
| `amsterdam-oost.qgs` | QGIS project file (references `locations.geojson`) |
| `export-osm.geojson` | Original OSM Overpass Turbo export (reference/backup) |
| `photos/` | 25 location photos (WhatsApp + screenshots) |

## Quick Start

### Interactive map (browser)
Open `map.html` in your browser. No server or build step needed.

### QGIS
Open `amsterdam-oost.qgs` in QGIS Desktop. The GeoJSON layer loads automatically.

## Features (HTML Map)

- **45 locations** with color-coded markers by category
  - 🔴 Restaurants — 🟡 Cafés — 🔵 Fast food — 🟢 Pubs — 🟠 Shops — 🟣 Supermarkets
- **17 photos** attached to 11 locations (click markers to view)
- **Sidebar** with search and category filter
- **Photo Manager** panel to drag-assign photos to locations
- **Click markers** to see details, photos, address, and coordinates
- **Drag markers** to reposition — coordinates update automatically
- **Add new points** — click "Add Point", then click the map
- **Export** — download updated GeoJSON with all changes
- **Lightbox** — click any photo to view full-size (Esc to close)

## Locations (45 total)

### Restaurants (11)
| Name | Address | Photos |
|------|---------|--------|
| Meram | Pretoriusstraat 22-H | — |
| Natraj | Transvaalstraat 5 | — |
| Fuku Ramen | Ingogostraat 14A | — |
| Miss Hotpot | Linnaeusstraat 64-H | — |
| Marina Plaza | Linnaeusstraat 74-H | — |
| The Cottage | Linnaeusstraat 88 | 4 photos |
| Eighty-Four | Oranje-Vrijstaatkade 25 | — |
| Nomads | Oranje-Vrijstaatkade 55 | — |
| Yemen Restaurant | Oranje-Vrijstaatkade 66 | — |
| Moche | Linnaeuskade 3-H | — |
| Safak | Linnaeusstraat | 1 photo |

### Cafés (7)
| Name | Address | Photos |
|------|---------|--------|
| The Cottage Shop & Deli | Linnaeusstraat 76-H | — |
| Cafecito | Linnaeusstraat 112-H | 2 photos |
| Meram Cafe | Linnaeusstraat 219 | 1 photo |
| Q Cafe | Oranje-Vrijstaatkade | — |
| Wakuli | Oranje-Vrijstaatkade | 3 photos |
| Bagels & Beans | Oranje-Vrijstaatkade 68 | — |
| Kwekkeboom | Land van Cocagneplein | — |

### Fast Food (5)
| Name | Address | Photos |
|------|---------|--------|
| Toko Sumatra Deli | Linnaeusstraat | — |
| FEBO | Linnaeusstraat 92 | 1 photo |
| Ayaz Döner | Linnaeusstraat 213 | 1 photo |
| Helin's Döner | Linnaeusstraat 221 | 1 photo |
| Burger 'n Shake | Land van Cocagneplein 1D | — |

### Pubs (4)
| Name | Address | Photos |
|------|---------|--------|
| Cafe Sport | Linnaeusstraat 102 | 2 photos |
| Ruk en Pluk | Linnaeusstraat | — |
| De Bierkantine | Oranje-Vrijstaatkade 69 | — |
| Blend Coffee and Wine | Oranje-Vrijstaatkade | — |

### Shops (10)
| Name | Address | Photos |
|------|---------|--------|
| Konet | Pretoriusstraat 10-H | — |
| Rum Baba | Pretoriusstraat 15 | — |
| Mas Atelier | Pretoriusstraat 33 | — |
| Flour.ish | Pretoriusstraat 37 | — |
| Grapedistrict | Linnaeusstraat | — |
| Biolicious | Linnaeusstraat 70-72 | — |
| Drankerij | Linnaeusstraat | — |
| Vitaminstore | Land van Cocagneplein 46 | — |
| De Bakkerszonen | Land van Cocagneplein 48 | — |
| Simon Lévelt | Waldenlaan 4 | — |
| Holland & Barrett | Waldenlaan 129 | — |
| Sahan | Waldenlaan 135 | — |

### Supermarkets (3)
| Name | Address | Photos |
|------|---------|--------|
| DekaMarkt | Pretoriusstraat 9 | — |
| Albert Heijn | Land van Cocagneplein 3 | — |
| Jumbo | Linnaeusstraat 245-H | 1 photo |

### Other (1)
| Name | Address | Photos |
|------|---------|--------|
| Aan De Kade | Linnaeuskade | — |

## Photos

25 photos in `photos/` — 17 are assigned to locations, 8 unassigned.

### Assigned photos
| Location | Files |
|----------|-------|
| The Cottage | `WhatsApp…16.31.58.jpeg`, `WhatsApp…16.31.59 (3).jpeg`, `Schermafbeelding…224728.png`, `Schermafbeelding…224703.png` |
| Cafe Sport | `WhatsApp…16.31.59 (2).jpeg`, `Schermafbeelding…224239.png` |
| Cafecito | `WhatsApp…16.31.59 (1).jpeg`, `WhatsApp…16.31.59.jpeg` |
| Wakuli | `WhatsApp…16.32.00 (2).jpeg`, `WhatsApp…16.32.00 (1).jpeg`, `Schermafbeelding…224901.png` |
| Helin's Döner | `WhatsApp…16.32.00.jpeg` |
| FEBO | `Schermafbeelding…225055.png` |
| Ayaz Döner | `Schermafbeelding…224751.png` |
| Meram Cafe | `Schermafbeelding…224822.png` |
| Safak | `Schermafbeelding…224802.png` |
| Jumbo | `Schermafbeelding…225001.png` |

### Unassigned photos
Use the Photo Manager in `map.html` to assign these:
- `WhatsApp Image 2026-02-05 at 13.10.12.jpeg`
- `WhatsApp Image 2026-02-05 at 13.10.12 (1).jpeg`
- `Schermafbeelding 2026-02-05 155352.png`
- `Schermafbeelding 2026-02-05 160039.png`
- `Schermafbeelding 2026-02-05 160129.png`
- `Schermafbeelding 2026-02-05 160144.png`
- `Schermafbeelding 2026-02-05 161524.png`
- `Schermafbeelding 2026-02-05 224843.png`

## Data Source

Location data was extracted from OpenStreetMap via [Overpass Turbo](https://overpass-turbo.eu/) (saved as `export-osm.geojson`). Coordinates are in WGS84 / EPSG:4326.
