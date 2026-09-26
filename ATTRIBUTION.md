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

The route 93 photo-gap reference photos (`reference-photos/route93-gaps-<stretch>/`: Putney Hill, Wimbledon Park Side
and Parkside, Wimbledon Village, Wimbledon Hill Road, Merton Road, Morden Road, Epsom Road and North Cheam; see
`docs/r93_photo_gaps.md`) are from Geograph (https://www.geograph.org.uk, CC BY-SA 2.0), Wikimedia Commons (each
file's own licence) and Flickr (Creative Commons licences only; non-commercial / no-derivatives ones are marked
`reference_only`). Each photo's author, licence, source URL and date are in its folder's `manifest.json`. They are
used as modelling references only and are not bundled into the game.
<!-- r93-web -->
The route 93 general-web reference photos (`reference-photos/route93-web-<stretch>/`) were collected from the
public web pages listed below; copyright stays with each site or photographer (licence as stated on the page,
otherwise unknown). Each photo's page URL, image URL and date are in its folder's `manifest.json`. They are used
as modelling references only and are not bundled into the game.

- AccessAble access guide (Tesco Wimbledon Morden Road Express): https://www.accessable.co.uk/tesco/access-guides/tesco-wimbledon-morden-road-express
- Arthur Lloyd (music hall and theatre history site): http://www.arthurlloyd.co.uk/WimbledonTheatre.htm
- CAMRA WhatPub: https://camra.org.uk/pubs/ganleys-irish-bar-morden-140249, https://camra.org.uk/pubs/george-inn-harvester-morden-140252, https://camra.org.uk/pubs/lord-nelson-north-cheam-141421, https://camra.org.uk/pubs/nonsuch-inn-north-cheam-141448, https://camra.org.uk/pubs/place/north-cheam-12831?sort=nearest, https://camra.org.uk/pubs/royal-surrey-pub-morden-140407
- Cinema Treasures (user-contributed photos): https://cinematreasures.org/theaters/32724
- Clay Street (agent), Asda Stonecot Hill investment brochure: https://www.claystreet.co.uk/wp-content/uploads/2024/09/Asda-Sutton.pdf
- Douglas & Gordon (estate agent listing): https://www.douglasandgordon.com/buy/property-details/50926/putney-hill-sw15/
- Douglas & Gordon listing: https://www.douglasandgordon.com/buy/property-details/34747/putney-hill-sw15/, https://www.douglasandgordon.com/buy/property-details/44811/putney-hill-sw15/, https://www.douglasandgordon.com/buy/property-details/45989/putney-hill-sw15/, https://www.douglasandgordon.com/buy/property-details/52296/ross-court-putney-hill-sw15/, https://www.douglasandgordon.com/buy/property-details/54897/devonshire-house-putney-hill-sw15/, https://www.douglasandgordon.com/buy/property-details/56127/putney-hill-sw15/, https://www.douglasandgordon.com/buy/property-details/56458/putney-hill-sw15/, https://www.douglasandgordon.com/buy/property-details/69591/putney-hill-sw15/, https://www.douglasandgordon.com/buy/property-details/76749/devonshire-house-putney-hill-sw15/, https://www.douglasandgordon.com/buy/property-details/80607/putney-hill-sw15/, https://www.douglasandgordon.com/rent/property-details/54843/devonshire-house-putney-hill-sw15/, https://www.douglasandgordon.com/rent/property-details/56811/putney-hill-sw15/, https://www.douglasandgordon.com/rent/property-details/80857/putney-hill-sw15/, https://www.douglasandgordon.com/rent/property-details/82055/putney-hill-sw15/
- Dupuytren's UK (clinic page): https://dupuytrensuk.com/wimbledon-cancer-centre-london/
- Firstplan (Putney Exchange project page): https://www.firstplan.co.uk/projects/putney-exchange/
- Foster Wilson Size (architects): https://fosterwilsonsize.com/projects/polka-theatre-wimbledon/
- Goodfellows listing: https://www.goodfellows.co.uk/property/end-terraced-house-for-sale-london-road-morden-sm4-id-gmo260199, https://www.goodfellows.co.uk/property/flat-for-sale-epsom-road-sutton-sm3-id-gsh260107, https://www.goodfellows.co.uk/property/flat-for-sale-london-road-cheam-sm3-id-gsh260078, https://www.goodfellows.co.uk/property/flat-for-sale-the-holt-london-road-sm4-id-gmo260254, https://www.goodfellows.co.uk/property/mid-terraced-house-for-sale-priory-road-cheam-sm3-id-gcv260200
- Grace Miller & Co (estate agent listing): https://gracemiller.co.uk/property/chalford-court-putney-hill-london-sw15-2/
- Hawes & Co listing: https://www.hawesandco.co.uk/property/flat-for-sale-parkside-house-high-street-sw19-id-hwv180148, https://www.hawesandco.co.uk/property/flat-for-sale-the-broadway-london-sw19-id-hsu250444, https://www.hawesandco.co.uk/property/flat-for-sale-the-broadway-london-sw19-id-hwb260368, https://www.hawesandco.co.uk/property/flat-for-sale-wimbledon-hill-road-london-sw19-id-hwv260066, https://www.hawesandco.co.uk/property/flat-for-sale-wimbledon-hill-road-wimbledon-sw19-id-hwv240136, https://www.hawesandco.co.uk/property/flat-for-sale-wimbledon-hill-road-wimbledon-sw19-id-hwv260058
- IanVisits: https://www.ianvisits.co.uk/articles/80611-80611/
- J D Wetherspoon: https://www.jdwetherspoon.com/pubs/the-nonsuch-inn-north-cheam/
- Layers of London: https://www.layersoflondon.org/map/records/hand-racquet
- London Churches in photographs (londonchurchbuildings.com): https://londonchurchbuildings.com/2015/01/25/st-winefride-merton-roadlatimer-road-wimbledon-roman-catholic/
- London Churches in Photographs (londonchurchbuildings.com): https://londonchurchbuildings.com/2015/01/25/emmanuel-stonecot-hilldudley-drive-morden/, https://londonchurchbuildings.com/2015/01/25/st-lawrence-london-road-morden/, https://londonchurchbuildings.com/2015/01/30/st-cecilia-stonecot-hill-north-cheam-roman-catholic/
- Love Wimbledon (Wimbledon BID): https://lovewimbledon.org/centre-court-shopping-rebrands-as-wimbledon-quarter/, https://lovewimbledon.org/prince-of-wales-reopens-after-six-figure-upgrade/
- MAS architecture (architects): https://www.masarchitecture.co.uk/2021/05/merton-rd-wimbledon/
- Merton Council, Morden Sub Area Neighbourhoods: 14 Morden (borough character study): https://www.merton.gov.uk/system/files?file=0266-14_morden.pdf
- Merton Council, Morden Sub Area Neighbourhoods: 18 Morden Park (borough character study): https://www.merton.gov.uk/system/files?file=0266-18_morden_park-2.pdf
- Merton Council, Wimbledon Broadway Conservation Area Design Guide (1999): https://www.merton.gov.uk/assets/Documents/0177_wimbledon_broadway_design_guide.pdf
- Merton Council, Wimbledon Hill Road Conservation Area Character Assessment: https://www.merton.gov.uk/assets/Documents/0177_wimbledon_hill_road_character_assessment.pdf
- Merton Council, Wimbledon Village Conservation Area Design Guide (property descriptions): https://www.merton.gov.uk/assets/Documents/0177_wimbledon_village_conservation_area_design_guide_p19-27.pdf, https://www.merton.gov.uk/assets/Documents/0177_wimbledon_village_conservation_area_design_guide_p28-40.pdf
- Merton Council: Merton Character Study, chapter 20i Morden: https://www.merton.gov.uk/system/files?file=chapter20i.pdf
- Merton Council: Morden Station Planning Brief (March 2014): https://www.merton.gov.uk/system/files/05a_morden_station_planning_brief_mar14.pdf
- Merton Historical Society, Bill Rudd Collection: https://mertonhistoricalsociety.org.uk/bill-rudd-collection-morden-shops-aberconway-road/, https://mertonhistoricalsociety.org.uk/bill-rudd-collection-morden-shops-crown-lane/, https://mertonhistoricalsociety.org.uk/bill-rudd-collection-morden-shops-london-road-102-106-81-117-morden-court-parade/, https://mertonhistoricalsociety.org.uk/bill-rudd-collection-morden-shops-london-road-even-numbers/, https://mertonhistoricalsociety.org.uk/bill-rudd-collection-morden-shops-london-road-odd-numbers/
- New London Architecture: https://nla.london/projects/baitul-futuh-mosque
- Open House Festival: https://programme.openhouse.org.uk/listings/3600
- Premier Inn (London Putney Bridge hotel images): https://www.premierinn.com/gb/en/hotels/england/greater-london/london/london-putney-bridge.html
- Premier Magazine: https://www.premiermagazine.biz/news-blog/property/meticulously-restored-by-octagon-eagle-house-has-fascinating-blue-plaque-heritage/
- propertyauctions.io (EIG auction listing): https://propertyauctions.io/listings/90aeca6ca6b2bf59a24d72ab3915e15d
- Pubs Galore: https://www.pubsgalore.co.uk/pubs/56983/
- Putney SW15 (local news site): https://www.putneysw15.com/info/concrisis001.htm, https://www.putneysw15.com/trading/conhighstopenings2111.htm
- Rightmove (sold house prices): https://www.rightmove.co.uk/house-prices/sw15/putney-hill.html, https://www.rightmove.co.uk/house-prices/sw19/parkside.html, https://www.rightmove.co.uk/house-prices/sw19/wimbledon-park-side.html
- Singer Vielle (investment agent), Costa Coffee 6 Morden Road sale particulars: https://previous.singervielle.com/previous-sales/properties/costa-coffee-london-wimbledon.html
- speel.me.uk (Bob Speel): http://www.speel.me.uk/chlondon/mordench.htm
- St Lawrence Church, Morden: https://stlawrencechurch.co.uk/about-us/history/
- Sutton Council, Draft Sutton's Character Study (June 2024): https://www.sutton.gov.uk/sites/default/files/2026-04/Draft%20Sutton%20Character%20Study%20v9.5%20(Reduced%20Size).pdf
- Taking Stock (Catholic Church buildings review, with Historic England): https://taking-stock.org.uk/building/wimbledon-south-st-winefride/
- Taking Stock (Catholic churches of England and Wales): https://taking-stock.org.uk/building/north-cheam-st-cecilia/
- The Dog & Fox (Young's) website: https://www.dogandfoxwimbledon.co.uk/
- The Spotted Horse (Young's) website: https://www.spottedhorse.co.uk/
- TrustedCare: https://www.trustedcare.co.uk/care-homes/heathland-court-bupa
- Urban Pubs & Bars (The Railway venue page): https://www.urbanpubsandbars.com/venues/the-railway
- useyourlocal.com: https://www.useyourlocal.com/pubs/prince-of-wales-merton-london-sw19-10582/
- Walking London one postcode at a time (blog): https://londonpostcodewalks.wordpress.com/2013/11/14/sw15-decline-and-fall/
- Wandsworth Council, Putney Embankment Conservation Area Appraisal and Management Strategy: https://www.wandsworth.gov.uk/media/1671/pe_caaandms.pdf
- Wandsworth Council, Putney Heath Conservation Area Appraisal and Management Strategy: https://www.wandsworth.gov.uk/media/1677/putney_heath_caaandms_final.pdf
- WhatPub (CAMRA pub guide, member photos): https://whatpub.com/pubs/SWL/2801/hand-racquet-wimbledon, https://whatpub.com/pubs/SWL/2829/horse-groom-merton, https://whatpub.com/pubs/SWL/2878/oneills-wimbledon, https://whatpub.com/pubs/SWL/2897/prince-of-wales-wimbledon, https://whatpub.com/pubs/SWL/2904/prince-of-wales-merton, https://whatpub.com/pubs/SWL/2973/old-frizzle-wimbledon, https://whatpub.com/pubs/SWL/2982/wibbas-down-inn-wimbledon
- Wimbledon Quarter (shopping centre website): https://wimbledonquarter.com/
- wimbledonvillage.com (Wimbledon Village Business Association directory): https://wimbledonvillage.com/food-drink/bars-pubs/dog-fox/, https://wimbledonvillage.com/food-drink/bars-pubs/rose-crown/, https://wimbledonvillage.com/food-drink/cafes/maison-st-cassien/, https://wimbledonvillage.com/food-drink/cafes/paul/, https://wimbledonvillage.com/food-drink/restaurants/bella-capri/, https://wimbledonvillage.com/food-drink/restaurants/cent-anni/, https://wimbledonvillage.com/food-drink/restaurants/cote/, https://wimbledonvillage.com/food-drink/restaurants/giggling-squid/, https://wimbledonvillage.com/food-drink/restaurants/ivy-cafe-wimbledon/, https://wimbledonvillage.com/food-drink/restaurants/megans-in-the-village/, https://wimbledonvillage.com/food-drink/restaurants/rajdoot/, https://wimbledonvillage.com/food-drink/restaurants/thai-tho/, https://wimbledonvillage.com/food-drink/stores/amathus/, https://wimbledonvillage.com/food-drink/stores/bayley-sage/, https://wimbledonvillage.com/food-drink/stores/checkout/, https://wimbledonvillage.com/food-drink/stores/jeroboams/, https://wimbledonvillage.com/food-drink/stores/sainsburys-local/, https://wimbledonvillage.com/health-beauty/beauty-spas-clinics/the-glass-house-clinic/, https://wimbledonvillage.com/health-beauty/hair-salons/pose-wimbledon/, https://wimbledonvillage.com/health-beauty/hair-salons/the-village-edit-head-to-toe-precision/, https://wimbledonvillage.com/health-beauty/medical-care/cancer-centre-london/, https://wimbledonvillage.com/health-beauty/medical-care/parkside-hospital/, https://wimbledonvillage.com/health-beauty/nail-salons/townhouse/, https://wimbledonvillage.com/health-beauty/opticians/ace-eyewear/, https://wimbledonvillage.com/health-beauty/opticians/david-clulow/, https://wimbledonvillage.com/health-beauty/opticians/jimmy-fairly/, https://wimbledonvillage.com/health-beauty/pharmacies/wimbledon-pharmacy/, https://wimbledonvillage.com/lifestyle-culture/wimbledon-village-war-memorial/, https://wimbledonvillage.com/services/home-property/cham/, https://wimbledonvillage.com/services/home-property/fuller-gilbert/, https://wimbledonvillage.com/services/home-property/hamptons-international-countrywide-group/, https://wimbledonvillage.com/services/home-property/holden-ford/, https://wimbledonvillage.com/services/home-property/knight-frank/, https://wimbledonvillage.com/services/home-property/marsh-parsons/, https://wimbledonvillage.com/services/home-property/savills/, https://wimbledonvillage.com/services/home-property/wimbledon-homes/, https://wimbledonvillage.com/services/workspace-office-services/village-office/, https://wimbledonvillage.com/shopping/books-card-gifts/wimbledon-village-news/, https://wimbledonvillage.com/shopping/charity-stores/british-red-cross/, https://wimbledonvillage.com/shopping/charity-stores/cancer-research-charity-shop/, https://wimbledonvillage.com/shopping/charity-stores/marys-living-giving/, https://wimbledonvillage.com/shopping/charity-stores/oxfam/, https://wimbledonvillage.com/shopping/charity-stores/shelter-wimbledon-village-boutique/, https://wimbledonvillage.com/shopping/charity-stores/st-raphaels-hospice/, https://wimbledonvillage.com/shopping/children/postmark/, https://wimbledonvillage.com/shopping/fashion/bash/, https://wimbledonvillage.com/shopping/fashion/joseph-azagury/, https://wimbledonvillage.com/shopping/fashion/sweaty-betty/, https://wimbledonvillage.com/shopping/fashion/trilogy/, https://wimbledonvillage.com/shopping/home-interiors/clarendon-fine-art/, https://wimbledonvillage.com/shopping/home-interiors/day-true/, https://wimbledonvillage.com/shopping/home-interiors/japanese-knife-company-limited/, https://wimbledonvillage.com/shopping/home-interiors/life-kitchens/, https://wimbledonvillage.com/shopping/jewellery/eternal-jewels/, https://wimbledonvillage.com/shopping/jewellery/michael-platt/, https://wimbledonvillage.com/shopping/pets/georges-dog-boutique/
- wimbledonvillage.com business directory: https://wimbledonvillage.com/health-beauty/medical-care/cancer-centre-london/
- Winkworth (estate agent listing): https://www.winkworth.co.uk/properties/sales/albemarle-wimbledon-park-side-london-sw19/SOU170066, https://www.winkworth.co.uk/properties/sales/fairlawns-putney-hill-london-sw15/PUT160270, https://www.winkworth.co.uk/properties/sales/langham-court-48-putney-hill-london-sw15/PUT170280
<!-- /r93-web -->
