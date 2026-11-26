# hunt-map-data

Public map data for an offline hunting map app. Data files only, no code.

## roads.pmtiles (release `roads-v1`)

Every road, two-track and trail in Arizona as vector tiles (PMTiles v3, zoom 7-13, layers `major`, `minor`, `trail`).

- All OpenStreetMap highways (from the Geofabrik Arizona extract), plus
- US Census TIGER/Line 2025 roads where OpenStreetMap has nothing within 40 m.

Attributes: `k` class (hwy, maj, road, svc, track, trail), `n` name, `s` surface (paved, dirt), `p` access (private, service), `src` (osm, tiger).

A road on this map is not necessarily open to the public. Check land status and the agency's travel maps.

## Licences

- Road data © OpenStreetMap contributors, available under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/). This file is a derived database and is offered under the ODbL.
- US Census Bureau TIGER/Line data is in the public domain.
