# Attribution

Map data © OpenStreetMap contributors (ODbL). https://www.openstreetmap.org/copyright

Contains Environment Agency information © Environment Agency copyright and/or database right 2026. Open Government Licence.

The Environment Agency data is the LIDAR Composite DTM and first- and last-return DSMs, 1 m resolution, from the
Defra Data Services Platform (https://environment.data.gov.uk). It is used for terrain, building heights and roof
shapes, and tree positions and sizes. Licence:
https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

The 2018 Environment Agency National LIDAR Programme 1 m intensity raster (tiles TQ2560, TQ2565, captured 7 Feb 2018)
is used for the 1 m detail of the aerial texture and ground-cover map, and for roof materials. Same licence as above.

Every course area (`data/areas/<area>/`: Sutton town centre, Carshalton village) is built from these same sources:
its own OpenStreetMap extract (including multipolygon relations: ponds, courtyard buildings), the LIDAR tiles and
intensity tiles covering it, and the same six Sentinel-2 scenes.

Contains modified Copernicus Sentinel data 2026. Sentinel-2 L2A surface reflectance (summer 2026 scenes, tile 30UXC),
accessed as Cloud-Optimised GeoTIFFs via the Earth Search STAC catalogue (https://earth-search.aws.element84.com/v1),
gives the colours of the aerial texture, ground cover and roofs. Copernicus Sentinel data are free, full and open
(https://sentinels.copernicus.eu/documents/247904/690755/Sentinel_Data_Legal_Notice).

The drivers' heads use the MediaPipe canonical face model (468-vertex mesh and triangles; Google, Apache License 2.0,
https://github.com/google-ai-edge/mediapipe).

The route 213 street-level reference photos (`reference-photos/route213-streetlevel/`) are KartaView frames
(https://kartaview.org), dash-cam photos by alexander-ar (2019), licensed CC BY-SA 4.0
(https://creativecommons.org/licenses/by-sa/4.0/). They have been cropped to remove the dashboard. Each photo's
source URL, author and capture date are in its folder's `manifest.json`. They are used as modelling references only
and are not bundled into the game.

The route 213 route-wide photo hunt's reference photos (`reference-photos/route213-hunt-<stretch>/`, found by
`tools/fetch_r213_hunt_photos.py`, listed in `docs/r213_photo_hunt.md`) are Geograph Britain and Ireland photos
(https://www.geograph.org.uk), each licensed CC BY-SA 2.0 (https://creativecommons.org/licenses/by-sa/2.0/) by its
photographer: Colin Smith, Hugh Venables, Marathon, Peter T, Roger Cornfoot, Roger Miller, Stacey Harris and
Stephen Craven. Each photo's source URL,
author, licence and date are in its folder's `manifest.json`. They are used as modelling references only and are not
bundled into the game.
