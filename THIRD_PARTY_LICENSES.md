# Third-Party Licenses and Services

This file identifies third-party software and services currently included, loaded, referenced, or used by Golf Shot GPS. The proprietary Golf Shot GPS license applies only to Enginity-owned materials.

## Leaflet 1.9.4

- Project: [Leaflet](https://leafletjs.com/)
- Source: [Leaflet 1.9.4](https://github.com/Leaflet/Leaflet/tree/v1.9.4)
- Delivery: JavaScript and CSS loaded from [unpkg](https://unpkg.com/) at `unpkg.com/leaflet@1.9.4`
- License: BSD 2-Clause License
- Compliance: Permits use in proprietary applications. It does not impose copyleft, source-disclosure, or modification-disclosure requirements. Redistributions must retain the following copyright notice, conditions, and disclaimer.

### Leaflet license notice

BSD 2-Clause License

Copyright (c) 2010-2023, Volodymyr Agafonkin

Copyright (c) 2010-2011, CloudMade

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

## Third-Party Services and Map Content

### Esri ArcGIS World Imagery

- Service: Esri ArcGIS World Imagery tiled map service
- Endpoint used by the application: `https://server.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer/tile/{z}/{y}/{x}`
- Current in-map attribution: `Tiles © Esri`
- Provider: Esri and the imagery/data providers represented in the service
- Terms: Esri imagery, services, and contributing-provider content remain subject to Esri's applicable terms and data-attribution requirements. They are not covered by the Golf Shot GPS proprietary license.

Esri's current developer documentation states that applications using ArcGIS services or content must display Esri and data-provider attribution, and that an ArcGIS Location Platform or ArcGIS Online account is required for current basemap services. Because Golf Shot GPS uses a legacy public `server.arcgisonline.com` endpoint without an application credential and shows only `Tiles © Esri`, the current public-use authorization, account requirements, usage limits, and complete attribution for this exact deployment must be confirmed with Esri before publication under the Enginity organization. The existing attribution acknowledges Esri but may not provide all contributing data-provider credits required for the imagery shown at a particular location.

- [Esri data attribution guidance](https://developers.arcgis.com/documentation/glossary/data-attribution/)
- [Esri legal terms](https://www.esri.com/en-us/legal/terms/master-agreement)

## Other Resources Reviewed

- The app uses operating-system font stacks only; no third-party web fonts are loaded or distributed.
- The Golf Shot GPS app icons and interface graphics are treated as Enginity-owned assets, not third-party components.
- No other JavaScript frameworks, plugins, icon libraries, or packaged software dependencies are present in the current repository.
