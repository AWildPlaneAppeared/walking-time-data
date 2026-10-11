# Walking Time data

Static data releases for Walking Time, a private, offline-first walking app made for one person. The app downloads these files from the GitHub releases of this repository. There is no server and no tracking.

## What a release contains

- `manifest.json`: the list of datasets, versions, file sizes and SHA-256 checksums.
- `walks-<n>.sqlite.xz`: walks in the Auckland region with derived facts (length, climb, difficulty, surfaces, facilities).
- `status-<n>.json.xz`: track status and closures.
- `tides-<n>.sqlite.xz`: tide predictions.
- `*.mbtiles`: offline map tiles (base map, terrain, aerial imagery, walk lines).
- `content-<n>.enc`: encrypted family content. It is private and cannot be read without the app.

## Sources and licences

- Crown Copyright: Department of Conservation Te Papa Atawhai 2026. DOC data is licensed under CC BY 4.0.
- Contains data sourced from the LINZ Data Service licensed for reuse under CC BY 4.0 (elevation models, aerial imagery, tide predictions).
- Map data © OpenStreetMap contributors, Open Database License (ODbL 1.0).
- Park, facility and coastline data © Auckland Council, CC BY 4.0. Track data © Auckland Council.
- Species observations from iNaturalist contributors, under each observation's own licence.
