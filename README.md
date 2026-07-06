# 🌍 Awesome Online GeoJSON & GIS Data

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome GeoJSON sources, web-based GIS tools, open geospatial data repositories, and niche map collections.

---

## 📑 Table of Contents

- [🛠️ GeoJSON Utilities & Editors](#%EF%B8%8F-geojson-utilities--editors)
- [📦 Downloadable GeoJSON Repositories](#-downloadable-geojson-repositories)
- [🔄 Format Converters](#-format-converters)
- [🌐 Global GIS Data Sources](#-global-gis-data-sources)
- [🗺️ OpenStreetMap Resources](#%EF%B8%8F-openstreetmap-resources)
- [🎯 Niche & Specialized Maps](#-niche--specialized-maps)
- [🏛️ Boundary & Administrative Data](#%EF%B8%8F-boundary--administrative-data)
- [🌊 Maritime & Marine Data](#-maritime--marine-data)
- [🏔️ Elevation & Terrain Data](#%EF%B8%8F-elevation--terrain-data)
- [🛰️ Satellite & Aerial Imagery](#%EF%B8%8F-satellite--aerial-imagery)
- [🌱 Environmental & Climate Data](#-environmental--climate-data)
- [📡 Real-time Feeds & APIs](#-real-time-feeds--apis)
- [📍 Geocoding & Routing APIs](#-geocoding--routing-apis)
- [🧩 Vector Tiles, TopoJSON & Tile Services](#-vector-tiles-topojson--tile-services)
- [🎨 SVG Maps](#-svg-maps)
- [📖 Place Names & Gazetteers](#-place-names--gazetteers)
- [🏞️ Protected Areas & Conservation Data](#%EF%B8%8F-protected-areas--conservation-data)
- [🏪 Specialized Data Portals](#-specialized-data-portals)
- [📚 Other Awesome Lists](#-other-awesome-lists)

---

## 🛠️ GeoJSON Utilities & Editors

*Repositories and tools specifically focused on GeoJSON formats and web mapping.*

* **[tmcw/awesome-geojson](https://github.com/tmcw/awesome-geojson)** - The definitive "awesome" list for GeoJSON. A curated catalogue of utilities, tools, and libraries designed to make working with GeoJSON easier.
* **[joewdavies/awesome-frontend-gis](https://github.com/joewdavies/awesome-frontend-gis)** - A collection of frontend GIS tools and geospatial resources for web development, including a dedicated section for GeoJSON.
* **[geojson.io](https://geojson.io/) / [GitHub](https://github.com/mapbox/geojson.io)** - A fast, simple tool for creating, viewing, and sharing spatial data. Essential for generating or validating GeoJSON files.
* **[Mapshaper](https://mapshaper.org/)** - An in-browser tool (and command-line utility) for editing, simplifying, and converting GeoJSON, TopoJSON, and Shapefiles.
* **[simonepri/geo-maps](https://github.com/simonepri/geo-maps)** - High-quality, programmatically generated GeoJSON maps of the world, ready for web use.
* **[geojson-maps.kyd.au](https://geojson-maps.kyd.au/)** - Download custom country selections as GeoJSON at 110m/50m/10m resolution.
* **[NextBillion.ai GeoJSON Editor](https://nextbillion.ai/blog/free-geojson-editor-tool)** - Free online GeoJSON editor for drawing points, lines, and polygons on a map.

## 📦 Downloadable GeoJSON Repositories

*GitHub repos and packages providing ready-to-use GeoJSON files.*

* **[datasets/geo-countries](https://github.com/datasets/geo-countries)** - Country polygons as GeoJSON for all world countries, derived from Natural Earth. Available on [DataHub](https://datahub.io/core/geo-countries).
* **[georgique/world-geojson](https://github.com/georgique/world-geojson)** - GeoJSON for all countries, areas (regions), and some states/provinces. Available via NPM and Composer.
* **[simonepri/geo-maps](https://github.com/simonepri/geo-maps)** - Programmatically generated GeoJSON maps — coastlines, countries, and urban areas at multiple zoom levels.
* **[Microsoft Building Footprints](https://github.com/microsoft/BuildingFootprints)** - Open GeoJSON data providing AI-generated building footprints for over 1.2 billion buildings globally.
* **[opengeos/planet-open-data](https://github.com/opengeos/planet-open-data)** - Footprints of Planet Open Data as GeoJSON.
* **[Overture Maps Foundation](https://overturemaps.org/)** - Open map data project backed by AWS, Meta, Microsoft, and TomTom. Releases global POI, buildings, transportation, and admin boundary datasets as GeoJSON/Parquet.

## 🔄 Format Converters

*Online tools for converting between geospatial formats.*

* **[GeoConverter](https://geoconverter.mikoding.com/)** - 100% client-side GIS format converter supporting 30+ vector and raster formats (GeoJSON, Shapefile, KML, GPX, GML, DXF, GeoPackage, TopoJSON, and more). Powered by GDAL via WebAssembly.
* **[QuickMapTools](https://www.quickmaptools.com/)** - Online toolset for downloading, converting, and inspecting geospatial data (boundaries, cities, Natural Earth) between GeoJSON, Shapefile, KML, TopoJSON, GeoPackage, FlatGeobuf, SVG, and DXF.
* **[MyGeoData Converter](https://mygeodata.cloud/converter/)** - Free online converter for GIS formats — supports GeoJSON, KML, Shapefile, GPX, DXF, CSV, and many more.
* **[AcuGIS 2GeoJSON](https://www.acugis.com/2geojson/)** - Free online converter from various GIS formats to GeoJSON.

## 🌐 Global GIS Data Sources

*Top-tier resources for high-quality, reliable, and accessible GIS vector and raster data.*

* **[Natural Earth Data](https://www.naturalearthdata.com/)** - The best starting point for cartographers. It provides public domain vector and raster datasets at various scales (1:10m, 1:50m, 1:110m), covering cultural and physical features.
* **[USGS EarthExplorer](https://earthexplorer.usgs.gov/)** - A primary source for satellite imagery (Landsat), elevation data (SRTM, NED), and LiDAR.
* **[NASA Earthdata](https://earthdata.nasa.gov/)** - Essential resource for scientific and environmental data, including global climate patterns, land cover, and satellite imagery (MODIS, Sentinel).
* **[ArcGIS Hub](https://hub.arcgis.com/)** - A massive repository containing over 350,000 open datasets from thousands of organizations and local municipalities globally.
* **[DIVA-GIS](https://www.diva-gis.org/gdata)** - Excellent for free, country-level data (administrative boundaries, climate, population, land cover).
* **[Free GIS Datasets (rtwilson.com)](https://freegisdata.rtwilson.com/)** - A categorised list of over 500 sites providing freely available geographic datasets.
* **[Global Map](https://globalmaps.github.io/)** - Consistent global GIS layers at 1km resolution (transportation, elevation, drainage, vegetation, land cover).
* **[AWS Earth](https://aws.amazon.com/earth/)** - Amazon Web Services-hosted open datasets including Landsat 8, Sentinel-2, NEXRAD, and OpenStreetMap.
* **[Google Earth Engine Data Catalog](https://developers.google.com/earth-engine/datasets/catalog/)** - A multi-petabyte catalog of satellite imagery and geospatial datasets.
* **[STAC Index](https://stacindex.org/)** - An index of known STAC (SpatioTemporal Asset Catalog) catalogs for discovering geospatial data.
* **[opengeos/geospatial-data-catalogs](https://github.com/opengeos/geospatial-data-catalogs)** - A list of open geospatial datasets available on AWS, Earth Engine, Planetary Computer, NASA CMR, and STAC Index.
* **[USGS The National Map](https://apps.nationalmap.gov/downloader/)** - Download US topographic maps, elevation data, hydrography, imagery, and transportation for the United States.
* **[SwissTopo Free Geodata](https://shop.swisstopo.admin.ch/en/free-geodata)** - Switzerland's official geodata free of charge (elevation, territory models, geological and national maps).
* **[Europa Technologies viaEuropa](https://www.europa.uk.com/)** - Hosted map and API platform delivering OceanWise marine data and global basemaps (free/commercial tiers).
* **[OneGeology](https://www.onegeology.org/)** - Global geological map data — WMS services for bedrock geology, surface geology, and hazard maps from national geological surveys.

## 🗺️ OpenStreetMap Resources

*Tools and services for extracting and downloading OpenStreetMap (OSM) data.*

* **[OpenStreetMap (OSM)](https://www.openstreetmap.org/)** - The most comprehensive source for up-to-date, community-driven vector data (roads, buildings, land use, etc.).
* **[Geofabrik](https://download.geofabrik.de/)** - Pre-processed OSM data extracts by continent or country in PBF, Shapefile, and OSM formats.
* **[OSM-Boundaries](https://osm-boundaries.com/)** - Interactive web interface to download administrative boundaries extracted from OpenStreetMap.
* **[HOTOSM Tools & Data](https://www.hotosm.org/tools-and-data)** - Tools and data exports from the Humanitarian OpenStreetMap Team.
* **[BBBike](https://download.bbbike.org/osm/)** - OSM data extracts for over 200 cities worldwide, updated weekly.
* **[Overpass Turbo](https://overpass-turbo.eu/)** - Web-based query tool for the OSM Overpass API — run custom spatial queries and export results as GeoJSON.
* **[OSMNames](https://osmnames.org/)** - Place names from OSM — downloadable, ranked, with bounding box and hierarchy. Ready for geocoding.

## 🎯 Niche & Specialized Maps

*Thematic maps focused on specific infrastructure, networks, or industries.*

* **[OpenInfraMap](https://openinframap.org/) / [GitHub](https://github.com/openinframap/openinframap)** - Power grids, telecom networks, oil & gas pipelines, solar generation, and water facilities — all from OSM.
* **[OpenRailwayMap](https://www.openrailwaymap.org/) / [GitHub](https://github.com/OpenRailwayMap/OpenRailwayMap)** - World railway infrastructure: tracks, stations, signals, electrification, gauges, and speeds.
* **[OpenSeaMap](https://openseamap.org/) / [GitHub](https://github.com/OpenSeaMap/online_chart)** - Free nautical chart with lighthouses, buoys, ports, fairways, and water depths.
* **[TeleGeography Submarine Cable Map](https://www.submarinecablemap.com/)** - Interactive map of global submarine internet cables and landing stations.
* **[OpenSnowMap](https://www.opensnowmap.org/) / [GitHub](https://github.com/OpenSnowMap-org/Website-opensnowmap.org)** - Ski pistes and winter sports infrastructure for downhill, cross-country, and backcountry skiing.
* **[OpenChargeMap](https://openchargemap.org/) / [GitHub](https://github.com/openchargemap)** - The world's largest open registry of EV charging locations (200K+ points, API, monthly exports).
* **[WaterwayMap](https://waterwaymap.org/)** - Canal and river navigation — locks, moorings, and waterway connections from OSM.

## 🏛️ Boundary & Administrative Data

*Sources specialized in political and administrative boundary polygons.*

* **[geoBoundaries](https://www.geoboundaries.org/)** - Open, peer-reviewed dataset of political administrative boundaries (ADM0 through ADM5) for every country. CC-BY 4.0.
* **[GADM](https://gadm.org/)** - High-resolution global administrative boundaries — 400,000+ administrative areas across all countries. Free for academic/non-commercial use.
* **[Eurostat GISCO](https://ec.europa.eu/eurostat/web/gisco/geodata)** - Administrative boundaries for Europe (countries, NUTS, LAU) at multiple scales. Free.
* **[GeoBoundary Data (EuroGeographics)](https://data.opendatascience.eu/geonetwork/srv/search?format=geoJSON)** - European administrative boundaries at 6 scale levels (100K–60M).
* **[Geocode Earth City Data](https://geocode.earth/data/boundary/city/)** - Free city/town/village boundary polygons in GeoJSON — based on Who's On First data.

## 🌊 Maritime & Marine Data

*Ocean boundaries, bathymetry, marine spatial data, and vessel tracking.*

* **[Global Fishing Watch](https://globalfishingwatch.org/) / [APIs](https://globalfishingwatch.org/our-apis/)** - Near real-time global fishing activity and vessel tracking data derived from AIS. Includes fishing effort, port visits, and SAR vessel detections (dark vessels).
* **[MarineRegions.org](https://www.marineregions.org/)** - Maritime boundaries geodatabase — Exclusive Economic Zones (EEZ), Territorial Seas (12NM), Contiguous Zones (24NM), Internal Waters, Archipelagic Waters, and High Seas.
* **[Flanders Marine Institute (VLIZ)](https://data.apps.fao.org/catalog/dataset/marine-boundaries-vliz)** - Official maritime boundaries dataset available via FAO catalog.
* **[GEBCO](https://www.gebco.net/)** - General Bathymetric Chart of the Oceans — global bathymetric grid and web services (WMS). The authoritative source for ocean depth data.
* **[EMODnet](https://emodnet.ec.europa.eu/)** - European Marine Observation and Data Network — seabed habitats, geology, bathymetry, hydrography, and human activities.

## 🏔️ Elevation & Terrain Data

*Digital elevation models, LiDAR, and topographic data sources.*

* **[OpenTopography](https://opentopography.org/)** - High-resolution topography data and tools, including LiDAR and DEM coverages.
* **[USGS 3DEP (The National Map)](https://apps.nationalmap.gov/downloader/)** - 3D Elevation Program data for the US — LiDAR point clouds, DEMs, contours.
* **[Viewfinderpanoramas DEM](http://www.viewfinderpanoramas.org/)** - Global digital elevation model data maintained by Jonathan de Ferranti.
* **[SRTM 30m Web Service](https://dwtkns.com/srtm30m/)** - Simple web service for getting SRTM 30m elevation data from NASA Earth Explorer.
* **[Reference Elevation Model of Antarctica (REMA)](https://www.pgc.umn.edu/data/rema/)** - High-resolution (8m) digital surface model of Antarctica.
* **[MapTiler Terrain Data](https://www.maptiler.com/terrain/)** - Global terrain RGB, quantized mesh (3D), hillshade, and contour lines from SRTM and ALOS. Free/paid tiers.
* **[Copernicus DEM](https://spacedata.copernicus.eu/collections/copernicus-digital-elevation-model)** - European Space Agency's global DEM at 30m and 90m resolution, free and open.

## 🛰️ Satellite & Aerial Imagery

*Sources for satellite imagery, aerial photos, and derived raster data.*

* **[Copernicus Open Access Hub](https://scihub.copernicus.eu/)** - The go-to source for high-resolution Sentinel satellite imagery (Sentinel-1 radar, Sentinel-2 optical) managed by the European Union.
* **[OpenAerialMap](https://openaerialmap.org/)** - A decentralized, open collection of satellite and UAV (drone) imagery.
* **[NASA GIBS](https://wiki.earthdata.nasa.gov/display/GIBS/)** - NASA Global Imagery Browse Services — near real-time satellite imagery as tiles via WMTS.
* **[ESA WorldCover](https://esa-worldcover.org/en/data-access)** - Global land cover product at 10m resolution for 2020/2021, based on Sentinel-1 and Sentinel-2.
* **[NASA Earth Observations (NEO)](https://neo.sci.gsfc.nasa.gov/)** - Global satellite imagery of environmental parameters (temperature, precipitation, vegetation, etc.).
* **[Sentinel-2 Cloudless (EOX)](https://s2maps.eu/)** - Beautiful, cloud-free global mosaic of Sentinel-2 data, available via WMTS.
* **[MapTiler Satellite](https://www.maptiler.com/satellite/)** - Global seamless satellite and aerial imagery with resolution locally up to 8cm/pixel. Free/paid tiers.

## 🌱 Environmental & Climate Data

*Climate, weather, land cover, and environmental GIS data.*

* **[CHELSA Climatologies](https://chelsa-climate.org/)** - Global climatologies at ~1km resolution for land surface temperature and precipitation. CC-BY.
* **[OpenLandMap](https://openlandmap.org/)** - Global environmental data — land cover, vegetation, soil, climate, terrain.
* **[SEDAC](https://sedac.ciesin.columbia.edu/)** - NASA Socioeconomic Data and Applications Center — population, infrastructure, environmental data.
* **[FAO Geospatial Data Portals](https://www.fao.org/geospatial/resources/data-portals/)** - Spatial data from the Food and Agriculture Organization of the UN.
* **[UNEP GEOdata](https://unepgrid.ch/en/platforms)** - UN Environment Programme data — global forest cover, evapotranspiration, temperatures, watershed boundaries.
* **[Global Climate Monitor](https://www.globalclimatemonitor.org/)** - Downloadable global climate data in GeoTIFF, KML, and CSV formats.
* **[IPUMS International](https://international.ipums.org/international/)** - Harmonized international census data for social science and health research.

## 📡 Real-time Feeds & APIs

*Live and regularly updated data services that return GeoJSON.*

* **[USGS Earthquake Hazards Program](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)** - Real-time earthquake data as GeoJSON feeds (past hour, day, 7 days, 30 days) at various magnitude thresholds.
* **[Open-Meteo](https://open-meteo.com/)** - Free weather forecast API — no API key required. Provides historical and forecast weather data.
* **[ZoomEarth](https://zoom.earth/)** - Live satellite imagery, weather maps, and storm tracking.
* **[NASA FIRMS](https://firms.modaps.eosdis.nasa.gov/)** - Real-time fire/hotspot data from MODIS and VIIRS. Available via WMS (free API key required).

## 📍 Geocoding & Routing APIs

*Services for converting addresses to coordinates and calculating routes.*

* **[Nominatim](https://nominatim.openstreetmap.org/)** - Free geocoding/reverse geocoding based on OSM data. Rate limit: 1 req/sec.
* **[OSRM](http://project-osrm.org/)** - Free routing API for car, bike, and foot profiles based on OSM data.
* **[Geocode Earth](https://geocode.earth/)** - Geocoding service with generous free tier, based on open data.
* **[OpenCage Geocoder](https://opencagedata.com/)** - Geocoding API aggregating multiple open data sources. Free tier available.
* **[MapTiler Geocoding API](https://www.maptiler.com/cloud/geocoding/)** - Geocoding, reverse geocoding, and IP location from MapTiler. Free tier available.
* **[GraphHopper](https://www.graphhopper.com/)** - Routing API with free tier, based on OSM data.
* **[ip-api.com](https://ip-api.com/)** - Free IP geolocation API (no key needed for non-commercial use).

## 🧩 Vector Tiles, TopoJSON & Tile Services

*Web services for basemap tiles, formats optimized for web performance, rendering, and topology.*

* **[topojson/world-atlas](https://github.com/topojson/world-atlas)** - The gold standard for high-quality, pre-simplified world country data in TopoJSON format (available in multiple resolutions).
* **[topojson/us-atlas](https://github.com/topojson/us-atlas)** - Pre-built TopoJSON files for US states, counties, and nation — from Census Bureau cartographic boundaries.
* **[mapbox/awesome-vector-tiles](https://github.com/mapbox/awesome-vector-tiles)** - The definitive "awesome" list for Mapbox Vector Tile (MVT) specifications, tools, and implementations.
* **[MapTiler Cloud & Data](https://www.maptiler.com/cloud/)** - Vector tiles, raster tiles, satellite, terrain, and geocoding. High-quality vector tiles downloads. Free tier with API key. Open source ecosystem.
* **[Protomaps Basemaps](https://github.com/protomaps/basemaps)** - Open source map symbology and basemaps based on OpenStreetMap.
* **[MapLibre Demo Tiles](https://github.com/maplibre/demotiles)** - Free, serverless demo vector tiles hosted on GitHub Pages — no keys required. Great for testing.
* **[OpenMapTiles](https://openmaptiles.org/)** - Open-source project and vector tile schema for creating vector map tiles from OSM data.
* **[Free WMS/WMTS Basemap URLs (2026)](https://geodocs.io/en/blog/list-of-free-wms-and-wmts-basemap-urls-2026)** - Curated list of free WMS and WMTS endpoints — OSM, USGS Topo, NASA GIBS, Sentinel-2, GEBCO, OneGeology, and more.
* **[NASA GIBS WMTS](https://gibs.earthdata.nasa.gov/wmts/epsg3857/best/wmts.xml)** - Near real-time satellite imagery layers (MODIS, VIIRS) via WMTS — open, no API key.
* **[USGS Topo WMTS](https://basemap.nationalmap.gov/arcgis/rest/services/USGSTopo/MapServer/WMTS/)** - USGS topographic basemap as tile service.
* **[EOX Sentinel-2 WMTS](https://tiles.maps.eox.at/wmts/1.0.0/WMTSCapabilities.xml)** - Cloud-free global Sentinel-2 mosaic via WMTS.
* **[Terrestris OSM WMS](https://ows.terrestris.de/osm/service?)** - OpenStreetMap rendered as WMS — free, no API key.
* **[qgis-data-sources](https://github.com/m-lmi/qgis-data-sources)** - Curated collection of public WMS, WMTS, WFS, XYZ, and REST connections for QGIS.
* **[TileServer-GL](https://github.com/maptiler/tileserver-gl)** - Self-host vector and raster map tiles with GL styles. Server-side rendering by MapLibre GL Native.

## 🎨 SVG Maps

*Scalable Vector Graphics for creating lightweight, stylized, and interactive web maps.*

* **[djaiss/mapsicon](https://github.com/djaiss/mapsicon)** - A massive collection of maps for nearly every country in SVG format, available in multiple sizes.
* **[amCharts Free SVG Maps](https://www.amcharts.com/svg-maps/)** - High-quality SVG maps of countries and regions in two detail levels. Free for non-commercial use (CC BY-NC 4.0). Also has an [SVG Map Generator](https://dojo.amcharts.com/svg-map-generator/).
* **[SVGMap Organization](https://svgmap.org/)** - An open-source project promoting decentralized, client-centric web mapping using SVG.
* **[react-simple-maps](https://github.com/zcreativelabs/react-simple-maps)** - Create beautiful SVG maps in React with minimal dependencies.
* **[MapSVG](https://mapsvg.com/maps)** - Free SVG vector maps — world, continents, and 100+ individual countries with internal subdivisions (states, provinces, counties).
* **[SimpleMaps Free SVG Maps](https://simplemaps.com/resources/svg-maps)** - Clean, web-optimized SVG world map (Robinson projection, 140KB) and US state maps. Free for commercial use with attribution.
* **[Free SVG Maps](https://freesvgmaps.com/)** - Editable SVG maps of world regions and countries — clean boundaries, suitable for presentations and design projects.
* **[FreeWorldMaps.net SVG](https://www.freeworldmaps.net/vector/map.html)** - Free SVG world map with Miller cylindrical projection and 30° graticule.
* **[Interactive SVG Maps](https://ahuseyn.github.io/interactive-svg-maps/)** - Interactive SVG maps of 164 UN member countries based on Natural Earth data. MIT license.
* **[QuickMapTools US Counties SVG](https://www.quickmaptools.com/us-counties-boundaries)** - US county boundaries available as SVG with each county as a separate path — ready for Illustrator, Figma, Inkscape.

## 📖 Place Names & Gazetteers

*Geographic names databases and gazetteer services.*

* **[GeoNames](https://www.geonames.org/)** - The most comprehensive open gazetteer — 11+ million place names with coordinates, elevation, population, and administrative hierarchy. Free via web services and data dumps.
* **[GEOnet Names Server (GNS)](https://geonames.nga.mil/geonames/GNSData/)** - Official U.S. government repository of foreign place names (outside US/Antarctica). Downloadable text files with lat/lng and feature classification. Public domain.
* **[USGS Geographic Names Information System (GNIS)](https://www.usgs.gov/us-board-on-geographic-names/domestic-names)** - Official repository of domestic (US) geographic names — 2+ million features including populated places, rivers, mountains, and landmarks.
* **[Who's On First (WOF)](https://whosonfirst.org/)** - Open, gazetteer-oriented geodata with concordance across multiple sources (GeoNames, OSM, etc.). Available as GeoJSON and SQLite bundles.
* **[openaddresses.io](https://openaddresses.io/)** - Open address data project — addresses from around the world, free to download.

## 🏞️ Protected Areas & Conservation Data

*Parks, reserves, and conservation area boundaries.*

* **[Protected Planet (WDPA)](https://www.protectedplanet.net/)** - World Database on Protected Areas — the most comprehensive global dataset of terrestrial and marine protected areas. Downloadable shapefiles.
* **[USGS PAD-US](https://www.usgs.gov/programs/gap-analysis-project/science/pad-us-data-download)** - Protected Areas Database of the US — fee, designation, easement, and proclamation areas. Geodatabase download.
* **[MPAtlas](https://old.mpatlas.org/)** - Marine protected area data with enhanced accuracy for selected regions — built on WDPA with national corrections.
* **[IUCN Green List](https://www.protectedplanet.net/en/thematic-areas/green-list)** - Sites meeting the IUCN global standard for protected area management excellence.

## 🏪 Specialized Data Portals

*Domain-specific geospatial data repositories.*

* **[Rextag Global Energy GIS Data](https://www.rextag.com/)** - Oil and gas pipelines, refineries, LNG terminals, and energy facilities data.
* **[IPIS Open Data](https://ipisresearch.be/)** - Data on natural resources, conflict, and human rights in sub-Saharan Africa.
* **[OCC Environmental Data Commons](https://www.occloud.io/)** - Repository for environmental public data sets of scientific interest.

## 📚 Other Awesome Lists

*Deep community-curated collections of geospatial data and software.*

* **[Awesome GIS](https://github.com/elasticlabs/awesome-gis)** - A massive, categorized list of GIS resources, software, and data portals.
* **[Awesome Geodata](https://github.com/kartoza/awesome-geodata)** - An extensive collection of geospatial data sources and services across different categories.
* **[Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial)** - Long list of geospatial tools and resources on GitHub.
* **[Awesome Open Geoscience](https://github.com/softwareunderground/awesome-open-geoscience)** - Curated list of open geoscience resources — seismic, geospatial, geochemistry, and more.
* **[Awesome Geospatial List](https://github.com/jerr0328/awesome-geospatial-list)** - Curated list of geospatial tools, data, tutorials, and information.
* **[Awesome Google Earth Engine](https://github.com/opengeos/Awesome-GEE)** - A curated list of Google Earth Engine resources.
* **[Awesome Earth Observation Code](https://github.com/elasticlabs/awesome-earthobservation-code)** - Curated list of tools, tutorials, and code for Earth Observation.
* **[Awesome Open Climate Science](https://github.com/pangeo-data/awesome-open-climate-science)** - Resources for atmospheric, ocean, climate, and hydrologic science.
* **[Awesome-Spatial](https://github.com/RoboDonut/awesome-spatial)** - Awesome list for geospatial in general.
* **[Awesome Historic(al) Maps](https://github.com/stark1tty/Awesome-Historic_al-Maps)** - Resources, databases, and tools related to historic maps.
* **[Awesome Coastal](https://github.com/chrisleaman/awesome-coastal)** - Resources for coastal engineers and scientists.
* **[Awesome Mining Data](https://github.com/Arpeggeo/awesome-mining-data)** - Curated list of open datasets in the mining industry — drilling, geology, geophysics, and geometallurgy.
* **[Railway Data Sources (RailToolkit)](https://github.com/railtoolkit/data-sources)** - A community-curated list of datasets and data sources relevant to railways worldwide — infrastructure, operations, and more.
* **[Awesome OpenStreetMap](https://github.com/osmlab/awesome-openstreetmap)** - Curated list of OSM-related projects, tools, and resources.
