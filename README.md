# RSL Map Project

[![Latest Release](https://img.shields.io/github/v/release/ObnoxiouslyNoxious/RSLMapProject)](https://github.com/ObnoxiouslyNoxious/RSLMapProject/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-View-blue)](https://obnox.dev/RSLMapProject/)

A web-based spawn point viewer for the [Random Spawn Locations (RSL)](https://steamcommunity.com/sharedfiles/filedetails/?id=3730705272) Mod for Project Zomboid.

## Features

- **Interactive map** — Click to view spawn point details
- **Multi-select filters** — Filter by Town, Type, Category, and Map Mods
- **Spawn point details** — View spawn point data and coordinates
- **Multiple maps** — Knox Country and Indiana support
- **Real-time search** — Find spawn points quickly

## Live Demo

**View it online:** [RSL Map Project](https://obnox.dev/RSLMapProject/)

## Usage

1. Open the live demo or host locally
2. Select a map from the dropdown (Knox Country or Indiana)
3. Use the filter buttons to narrow down spawn points by Town, Type, or Category
4. Hover over a spawn point on the map to view details

## Local Development

To run locally, simply open `index.html` in a web browser — no server required.

```bash
# Or use a local server
python -m http.server 8080
```

## How It Works

- Reads spawn point data from `rsl_state.json`
- Renders an interactive map with spawn point markers
- Provides filtering, searching, and copy functionality
- All processing happens client-side (no backend required)

## Related

- [Random Spawn Locations Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=3730705272)
- [RSL Index (Spreadsheet)](https://obnox.dev/RSLSheet/)