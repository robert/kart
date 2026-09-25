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

The route 93 Wimbledon town centre reference photos (`reference-photos/route93-wimbledon/`: Wimbledon Hill Road,
Wimbledon Bridge, The Broadway, Merton Road to South Wimbledon) are from Geograph (https://www.geograph.org.uk,
CC BY-SA 2.0, by their photographers), Wikimedia Commons (https://commons.wikimedia.org, each under its own licence)
and Flickr (https://www.flickr.com, Creative Commons licences only). Each photo's author, licence, source URL, date
and position are in the folder's `manifest.json`; Flickr photos under non-commercial or no-derivatives licences are
marked `reference_only`. They are used as modelling references only and are not bundled into the game.

The route 213 route-wide photo hunt's reference photos (`reference-photos/route213-hunt-<stretch>/`, found by
`tools/fetch_r213_hunt_photos.py`, listed in `docs/r213_photo_hunt.md`) are Geograph Britain and Ireland photos
(https://www.geograph.org.uk), each licensed CC BY-SA 2.0 (https://creativecommons.org/licenses/by-sa/2.0/) by its
photographer: Colin Smith, Hugh Venables, Marathon, Peter T, Roger Cornfoot, Roger Miller, Stacey Harris and
Stephen Craven. Each photo's source URL,
author, licence and date are in its folder's `manifest.json`. They are used as modelling references only and are not
bundled into the game.

The bus route 93 Wimbledon Village reference photos (`reference-photos/route93-wimbledonvillage/`: Wimbledon Park Side,
Parkside, High Street Wimbledon and the top of Wimbledon Hill Road) are from Geograph (https://www.geograph.org.uk,
CC BY-SA 2.0), Wikimedia Commons (https://commons.wikimedia.org, each file's own licence, mostly CC BY-SA), Flickr
(https://www.flickr.com, Creative Commons licences only; the NC/ND ones are marked `reference_only`), KartaView
(https://kartaview.org, CC BY-SA 4.0) and Panoramax (https://panoramax.xyz, CC BY-SA 4.0). Each photo's source URL,
author, licence and date are in the folder's `manifest.json`. They are used as modelling references only and are not
bundled into the game.

The bus route 93 Putney reference photos (`reference-photos/route93-putney/`: Putney Bridge station, Fulham High
Street, Putney Bridge, Putney High Street to Putney station) come from Geograph (https://www.geograph.org.uk, each
photo © its named contributor, licensed CC BY-SA 2.0, https://creativecommons.org/licenses/by-sa/2.0/), Wikimedia
Commons (each file's own licence and author), Flickr (Creative Commons licences only; the non-commercial and
no-derivatives ones are marked `reference_only`) and KartaView (dash-cam frames, CC BY-SA 4.0). Each photo's source
URL, author, licence and date are in the folder's `manifest.json`. They are used as modelling references only and
are not bundled into the game.

The route 93 Putney Hill reference photos (`reference-photos/route93-putneyhill/`: Putney station, Putney Hill,
Tibbet's Ride, Tibbet's Corner and the start of Wimbledon Park Side) come from Geograph (https://www.geograph.org.uk,
CC BY-SA 2.0), Wikimedia Commons (https://commons.wikimedia.org, each file under its own licence, mostly CC BY-SA),
Flickr (https://www.flickr.com, Creative Commons licences only; the non-commercial or no-derivatives ones are marked
`reference_only`) and KartaView (https://kartaview.org, CC BY-SA 4.0). Each photo's author, licence, source URL and
capture date are in the folder's `manifest.json`. They are used as modelling references only and are not bundled
into the game.

The route 93 Merton reference photos (`reference-photos/route93-merton/`: Merton Road, South Wimbledon, Morden Road,
Merton Park, the edge of Morden Hall Park and Morden town centre) are from Geograph (https://www.geograph.org.uk,
CC BY-SA 2.0), Wikimedia Commons and Flickr (each under the licence named for it: CC BY, CC BY-SA or public domain).
Each photo's author, licence, source URL and date are in the folder's `manifest.json`. They are used as modelling
references only and are not bundled into the game.

<!-- mapillary -->
The route 93 Mapillary street-level reference photos (`reference-photos/route93-mapillary-<stretch>/`: `route93-mapillary-merton`, `route93-mapillary-morden`, `route93-mapillary-putney`, `route93-mapillary-wimbledon`, `route93-mapillary-wimbledoncommon`) are Mapillary images (https://www.mapillary.com), © Mapillary contributors, licensed CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/). 360° panoramas have been cut into perspective crops. Contributors: cueditsmaps, ecatmur, gness, HandyHat, julianlb, mappingmerton, modielnadi, trekviewed. Each photo's image id, source URL, creator, capture date and crop are in its folder's `manifest.json`. They are used as modelling references only and are not bundled into the game.
<!-- /mapillary -->
The route 93 reference photos for Morden town centre and Morden Park to North Cheam
(`reference-photos/route93-morden/`, `reference-photos/route93-northcheam/`) come from Geograph (CC BY-SA 2.0,
https://www.geograph.org.uk), Wikimedia Commons (each file's own licence, mostly CC BY-SA), Flickr (Creative Commons
licences only; non-commercial / no-derivatives ones are marked `reference_only`), KartaView (CC BY-SA 4.0) and
Panoramax. Each photo's author, licence, source URL and date are in its folder's `manifest.json`. They are used as
modelling references only and are not bundled into the game.
