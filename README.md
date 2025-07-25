# Awesome Geospatial   [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Long list of geospatial analysis tools. Geospatial analysis, or just spatial analysis, is an approach to applying statistical analysis and other analytic techniques to data which has a geographical or spatial aspect.

![427672_2794027726746_176065793_n](https://user-images.githubusercontent.com/7756611/48104109-2f465b80-e219-11e8-81bb-f6066e6a1be8.jpg)

- [Awesome Geospatial](#awesome-geospatial)
    - [Database](#database)
    - [Image Classification & DIP Software](#image-classification--dip-software)
    - [Geographic Information System](#geographic-information-system)
    - [Web Map Development](#web-map-development)
    - [Web Map Server](#web-map-server)
    - [Radar](#radar)
    - [Lidar](#lidar)
    - [3D Application](#3d-application)
    - [Geographic Data Mining](#geographic-data-mining)
    - [GNSS/INS Post Processing](#gnss/ins-post-processing)
    - [Atmospheric Correction](#atmospheric-correction)
    - [Agent-based Modeling](#agent-based-modeling)
    - [Landscape Metrics](#landscape-metrics)
    - [Landscape Modelling](#landscape-modelling)
    - [Spatial Optimization](#spatial-optimization)
    - [Libraries](#libraries)
    - [PaaS - Platform as a Service](#paas---platform-as-a-service)
    - [SaaS - Software as a Service](#saas---software-as-a-service)
    - [DaaS - Data as a Service](#daas---data-as-a-service)
    - [Google Earth Engine](#google-earth-engine)
    - [Deep Learning](#deep-learning)
    - [C](#c-1)
    - [C++](#c)
    - [C Sharp](#c-sharp)
    - [Clojure](#clojure)
    - [Crystal](#crystal)
    - [CSS](#css)
    - [Dart](#dart)
    - [Delphi](#delphi)
    - [Elixir](#elixir)
    - [Fortran](#fortran)
    - [Go](#go)
    - [Groovy](#groovy)
    - [Haskell](#haskell)
    - [IDL](#idl)
    - [Java](#java)
    - [JavaScript](#javascript)
    - [Julia](#julia)
    - [Kotlin](#kotlin)
    - [Lisp](#lisp)
    - [Lua](#lua)
    - [MATLAB](#matlab)
    - [Nim](#nim)
    - [Perl](#perl)
    - [PHP](#php)
    - [Python](#python)
    - [R](#r)
    - [Ruby](#ruby)
    - [Rust](#rust)
    - [Scala](#scala)
    - [Swift](#swift)
    - [Mobile Development](#mobile-development)
    - [Geospatial Big Data](#geospatial-big-data)
    - [Visualization](#visualization)
    - [Tools](#tools)
    - [Cheat sheets](#cheat-sheets)
    - [Data Sources](#data-sources)
    - [Resources](#resources)
    - [Free and Open Source Books](#free-and-open-source-books)
    - [Podcasts](#podcasts)
    - [Conferences](#conferences)
    - [References](#references-and-other-awesome-lists)

- - -

## Database

* [3D CityDB](http://www.3dcitydb.org/) - A free 3D geo database to store, represent, and manage virtual 3D city models on top of a standard spatial relational database. The database model contains semantically rich, hierarchically structured, multi-scale urban objects facilitating complex GIS modeling and analysis tasks, far beyond visualization.
* [Cloudant](https://cloudant.com/) - IBM noSQL database that supports spatial data (GeoJSON).
* [DB2 Spatial Extender](http://www-03.ibm.com/software/products/en/db2spaext) - Spatial Extender allows you to store, manage, and analyze spatial data in DB2.
* [GeoCouch](https://github.com/couchbase/geocouch) - GeoCouch is a spatial extension for Couchbase and Apache CouchDB.
* [Geopackage](https://www.geopackage.org/) - SQLite spatial extension. More powerful than its older brother Spatialite.
* [H2GIS](https://github.com/orbisgis/h2gis) - A spatial extension of the H2 database.
* [Hastings](https://github.com/cloudant-labs/hastings) - GeoSpatial Search for CouchDB 2
* [Informix Spatial](https://www.ibm.com/docs/en/informix-servers/14.10?topic=guide-getting-started-spatial-data) - Informix spatial extension.
* [Microsoft SQL Server](https://docs.microsoft.com/en-us/sql/relational-databases/spatial/spatial-data-sql-server) - Microsoft SQL/SQL Azure spatial features. All the spatial functionality is also available as a .NET library (can be downloaded using nuget)
* [MobilityDB](https://github.com/ULB-CoDE-WIT/MobilityDB) - An extension to the Postgres database which adds support for temporal and spatio-temporal objects
* [MongoDB](https://www.mongodb.com/) - Also supports GeoJSON and spatial indexes.
* [MySql Spatial](https://dev.mysql.com/doc/refman/8.0/en/spatial-analysis-functions.html) - MySql spatial extension.
* [Neo4j Spatial](https://github.com/neo4j-contrib/spatial) - Library of spatial utilities for Neo4j.
* [Oracle Spatial](http://www.oracle.com/us/products/database/options/spatial/overview/index.html) - Oracle database spatial extension.
* [OrientDB](https://github.com/orientechnologies/orientdb) - OrientDB is an Open Source Multi-Model NoSQL DBMS with the support of Native Graphs, Documents Full-Text, Reactivity, Geo-Spatial and Object Oriented concepts.
* [PgRouting](https://pgrouting.org/) - pgRouting extends the PostGIS / PostgreSQL geospatial database to provide geospatial routing functionality.
* [PostGEESE](https://duckdb.org/2023/04/28/spatial.html) - A spatial extension for DuckDB.
* [PostGIS Vector Tile Utils](https://github.com/mapbox/postgis-vt-util) - A set of PostgreSQL functions that are useful when creating vector tile sources.
* [PostGIS](http://postgis.net/) - PostgreSql spatial extension.
* [Rasdaman](http://www.rasdaman.org/) - Array database that allows storing and querying massive multi-dimensional arrays, such as sensor, image, simulation, and statistics data appearing in domains like earth, space, and life science.
* [SciDB](http://www.paradigm4.com/) - Array database designed for multidimensional data management and analytics common to scientific, geospatial, financial, and industrial applications.
* [Spatialite](http://www.gaia-gis.it/gaia-sins/) - SQLite spatial extension.
* [Teradata Geospatial Feature](https://docs.teradata.com/r/Teradata-VantageTM-Geospatial-Data-Types/March-2019/Geospatial-Data/Geospatial-Information) - Teradata spatial extension for DW and BI.
* [Tile38](https://github.com/tidwall/tile38) - Tile38 is a geospatial database, spatial index, and realtime geofence.
* [TileDB](https://github.com/TileDB-Inc/TileDB) - TileDB is a powerful engine for storing and accessing dense and sparse multi-dimensional arrays, which can help you model any complex data efficiently.
* [yogrt](https://github.com/Anagraph/yogrt) - A simple templating tool for importing GIS data to PostGIS


## Image Classification & DIP Software

* [ArcMap Raster Edit Suite](https://github.com/haoliangyu/ares) - An ArcMap Addin that enables manual editing of single pixels on raster layer.
* [ContextCapture](https://www.bentley.com/software/contextcapture/) - ContextCapture enables you to automatically generate multi-resolution 3D models at any scale and precision.
* [Correlator3D](https://www.simactive.com/correlator3d-mapping-software-features) - High-end photogrammetry suite.
* [Dinamica EGO](http://csr.ufmg.br/dinamica/) - Dinamica EGO consists of a sophisticated platform for environmental modeling.
* [e-Foto](http://www.efoto.eng.uerj.br/en) - Free and open source digital photogrammetric workstation.
* [eCognition](https://geospatial.trimble.com/products-and-solutions/ecognition) - GEOBIA software.
* [ENVI](http://www.harrisgeospatial.com/ProductsandSolutions/GeospatialProducts/ENVI.aspx) - Geospatial image processing and classification software.
* [ERDAS](http://www.hexagongeospatial.com/products/producer-suite/erdas-imagine) - Geospatial image processing and classification software.
* [gdal2tilesp](https://github.com/pramsey/gdal2tilesp) - This enhancement to the gdal2tiles.py script includes additional features.
* [Global Mapper](http://www.bluemarblegeo.com/products/global-mapper.php) - Geospatial and remote sensing data analysis.
* [Guidos Toolbox](http://forest.jrc.ec.europa.eu/download/software/guidos/) - Some GDAL functionalities and includes MSPA (Morphological Spatial Pattern Analysis) for connectivity maps.
* [IDL](http://www.harrisgeospatial.com/ProductsandSolutions/GeospatialProducts/IDL.aspx) - IDL is a programming language used for data analysis and image processing programming.
* [INPHO](https://geospatial.trimble.com/products-and-solutions/trimble-inpho) - INPHO is a Digital Photogrammetry Software.
* [Interimage](http://www.lvc.ele.puc-rio.br/projects/interimage/) - Open Source GEOBIA software.
* [Matlab](http://www.mathworks.com/products/matlab/) - Multi-paradigm numerical computing environment and fourth-generation programming language.
* [Metashape](https://www.agisoft.com/) - Agisoft Metashape is a stand-alone software product that performs photogrammetric processing of digital images.
* [MultiSpec](https://engineering.purdue.edu/~biehl/MultiSpec/index.html) - A Freeware Multispectral Image Data Analysis System.
* [OSSIM](http://trac.osgeo.org/ossim/) - Suite of geospatial libraries and applications used to process imagery, maps, terrain, and vector data.
* [PCI Geomatica](http://www.pcigeomatics.com/software/geomatica/professional) - Remote sensing software package for image processing
* [rasterix](https://github.com/mogasw/rasterix) - Rasterix is a cross-platform utility built around the GDAL library and the Qt framework designed to process geospatial raster data.
* [RealityCapture](https://www.realitycapture-training.com/) - Photogrammetry software.
* [SNAP](https://step.esa.int/main/download/snap-download/) - SNAP is an open source common architecture for ESA Toolboxes ideal for the exploitation of Earth Observation data.
* [Spring](http://www.dpi.inpe.br/spring/) - GIS and remote sensing image processing system with an object-oriented data model.
* [TerrSet](https://clarklabs.org/terrset/) - TerrSet (formerly IDRISI) is an integrated geographic information system (GIS) and remote sensing software
* [The Sentinel Toolbox](https://sentinel.esa.int/web/sentinel/toolboxes) - The Sentinel Toolboxes consists of a collection of processing tools, data product readers and writers and a display and analysis application to process Sentinel data.
* [TIMESAT](http://web.nateko.lu.se/timesat/timesat.asp?cat=0) - TIMESAT is a software package for analysing time-series of satellite sensor data.
* [WebODM](https://www.opendronemap.org/webodm/) - Generate maps, point clouds, DEMs and 3D models from aerial images.


## Geographic Information System

* [ArcGIS Pro](https://pro.arcgis.com/en/pro-app/) - Fully 64-bit version of ArcGIS with new GUI and 2D/3D integration.
* [ArcGIS](https://www.arcgis.com/features/) - GIS for working with maps and geographic information.
* [AutoCAD Map 3D](http://www.autodesk.com.br/products/autocad-map-3d/overview) - GIS AutoCAD integration.
* [FME Desktop](https://www.safe.com/fme/fme-desktop/) - FME is an integrated collection of Spatial ETL tools for data transformation and data translation.
* [GC2](http://www.mapcentia.com/en/product/) - GC2 is an enterprise platform GIS (open source)
* [GeoDa](http://geodacenter.github.io/) - Spatial data analysis software.
* [Geomedia](https://hexagon.com/products/geomedia) - Commercial GIS.
* [GRASS GIS](https://grass.osgeo.org/) - GRASS (Geographic Resources Analysis Support System) is a free and open source GIS.
* [gvSIG](http://www.gvsig.com/en) - Free and open source GIS.
* [ILWIS](http://52north.org/communities/ilwis/ilwis-open) - Integrated Land and Water Information System (ILWIS) is a remote sensing and GIS software.
* [LuciadFusion](http://www.luciad.com/solutions/luciadfusion) - An all-in-one server solution for your data publication workflow and geospatial data management
* [Manifold System](http://www.manifold.net/) - Commercial GIS.
* [Mapbox Studio](https://github.com/mapbox/mapbox-studio-classic) - Desktop application for vector tile driven map design.
* [MapInfo](https://www.geograph.com.br/mapinfo) - Commercial GIS.
* [MapWindow GIS](http://www.mapwindow.org/) - Free and open source desktop geographic information system.
* [MicroImages TNTgis](https://www.microimages.com/) - Commercial GIS.
* [OpenJUMP](http://openjump.org/) - Open source Java GIS.
* [QGIS](http://www.qgis.org/en/site/) - Cross-platform free and open-source desktop geographic information system.
* [SAGA](http://www.saga-gis.org/en/index.html) - SAGA is the abbreviation for System for Automated Geoscientific Analyses.
* [Smallworld](https://www.gegridsolutions.com/geospatial/catalog/smallworld_core.htm) - Commercial GIS.
* [Terraview](http://www.obt.inpe.br/OBT/assuntos/projetos/terralib-terraview) - GIS application built using the TerraLib  GIS library.
* [uDig](http://udig.refractions.net/) - A GIS Framework for Eclipse (Java) and also a GIS software.


## Web Map Development

* [angular-azure-maps](https://github.com/Acaisoft/angular-azure-maps) - Angular 6 Azure Maps is a wrapped MS Azure Map on Angular.
* [ArcGIS JS App Generator](https://github.com/odoe/generator-arcgis-js-app) - This is a yeoman generator for ArcGIS API for JavaScript applications.
* [azure-maps-animations](https://github.com/Azure-Samples/azure-maps-animations) - A rich library of animations for use with the Azure Maps Web SDK.
* [azure-maps-fullscreen-control](https://github.com/Azure-Samples/azure-maps-fullscreen-control) - An Azure Maps Web SDK module that provides a control to display the map in fullscreen mode.
* [azure-maps-geolocation-control](https://github.com/Azure-Samples/azure-maps-geolocation-control) - An Azure Maps Web SDK module that provides a control that uses the browser's geolocation API to locate the user on the map.
* [azure-maps-gridded-data-source](https://github.com/Azure-Samples/azure-maps-gridded-data-source) - A module for the Azure Maps Web SDK that provides a data source that clusters data points into cells of a grid area.
* [azure-maps-selection-control](https://github.com/Azure-Samples/azure-maps-selection-control) - An Azure Maps Web SDK module that provides controls for selecting data in a data source using drawing tools or by requesting a route range polygon.
* [azure-maps-services-ui](https://github.com/Azure-Samples/azure-maps-services-ui) - A set of web UI controls that wrap the Azure Maps REST services.
* [azure-maps-swipe-map](https://github.com/Azure-Samples/azure-maps-swipe-map) - A module for the Azure Maps Web SDK that allows swiping between two overlapping maps, ideal for comparing two overlapping data sets.
* [azure-maps-sync-maps](https://github.com/Azure-Samples/azure-maps-sync-maps) - An Azure Maps Web SDK module that synchronizes the cameras of two or more maps.
* [Bertin.js](https://github.com/neocarto/bertin) - A JavaScript library for visualizing geospatial data and make thematic maps for the web.
* [CesiumJS](https://cesium.com/platform/cesiumjs/) - An open-source JavaScript library for world-class 3D globes and maps.
* [CMV - The Configurable Map Viewer](https://github.com/cmv/cmv-app) - CMV is a community-supported open source mapping framework. CMV works with the Esri JavaScript API, ArcGIS Server, ArcGIS Online and more.
* [deck.gl](https://deck.gl) - A WebGL-powered framework for visual exploratory data analysis of large datasets.
* [Flare Cluster Layer](https://github.com/nickcam/FlareClusterLayer) - ArcGIS javascript custom graphics layer. Creates clusters and creates flares for clusters.
* [geojson-vt](https://github.com/mapbox/geojson-vt) - A highly efficient JavaScript library for slicing GeoJSON data into vector tiles on the fly.
* [GeoNode](http://geonode.org/) - A web-based application and platform for developing geospatial information systems (GIS) and for deploying spatial data infrastructures (SDI).
* [Google Maps API Polyline String Decoder](https://github.com/mgd722/decode-google-maps-polyline) - Function that will convert encoded polyline strings (as returned by the Google Maps API) into a list of lat/lon pairs.
* [jVectorMap](https://jvectormap.com/) - jVectorMap is a vector-based, cross-browser and cross-platform component for interactive geography-related data visualization on the web. It provides numerious features like smooth zooming and panning, fully-customizable styling, markers, labels and tooltips.
* [L7](https://github.com/antvis/L7) - Large-scale WebGL-powered Geospatial Data Visualization By Ant Financial
* [Leaflet.MapboxVectorTile](https://github.com/SpatialServer/Leaflet.MapboxVectorTile) - A Leaflet Plugin that renders Mapbox Vector Tiles on HTML5 Canvas.
* [Leaflet](http://leafletjs.com/) - Open-Source JavaScript Library for Mobile-Friendly Interactive Maps.
* [LuciadRIA](http://www.luciad.com/solutions/luciadria) - A JavaScript library for 3D globes and maps, with support for military symbology and desktop-like performance
* [Mapbox GL JS](https://www.mapbox.com/mapbox-gl-js/api/) - Mapbox GL JS is a JavaScript library that uses WebGL to render interactive maps from vector tiles and Mapbox styles.
* [MapLibre GL](https://github.com/maplibre/maplibre-gl-js) - Is a community led fork derived from Mapbox GL JS prior to their switch to a non-OSS license.
* [MapLineDraw](https://github.com/patrsc/MapLineDraw) - An open source web application for drawing smooth curves (splines) on a map, suitable for sketching or measuring railway lines or roads.
* [Mapzen Tangram](https://github.com/tangrams/tangram) - JavaScript library for rendering 2D & 3D maps live in a web browser with WebGL, supports MVT, GeoJSON, TopoJSON.
* [Ol-ext](https://viglino.github.io/ol-ext/) - Cool extensions for OpenLayers (ol) - animated clusters, CSS popup, Font Awesome symbol renderer, charts for statistical map (pie/bar), layer switcher, wikipedia layer, animations, canvas filters.
* [OpenGlobus](https://www.openglobus.org/) - A javascript library designed to display interactive 3d maps and planets with map tiles, imagery and vector data, markers and 3d objects. It uses the WebGL technology, open source and completely free.
* [OpenLayers](http://openlayers.org/) - High-performance, feature-packed library for creating interactive maps on the web.
* [Oskari](https://oskari.org/) - Framework for easily building multipurpose web mapping applications utilizing distributed Spatial Data Infrastructures like INSPIRE.
* [react-azure-maps](https://github.com/WiredSolutions/react-azure-maps) - React Wrapper for azure-maps-control.
* [TerriaJS](https://github.com/TerriaJS/terriajs) - A library for building rich, web-based geospatial data explorers.
* [titiler](https://github.com/developmentseed/titiler) - A dynamic Web Map tile server.
* [v-mapbox](https://github.com/geospoc/v-mapbox) - Vue.js wrapper for `mapbox-gl-js`.
* [vue-azure-maps](https://github.com/rickyruiz/vue-azure-maps) - Integrate Azure Maps in your Vue application.


## Web Map Server

* [52North WPS](http://52north.org/communities/geoprocessing/wps/index.html) - The 52°North Web Processing Service (WPS) enables the deployment of geo-processes on the web in a standardized way. It features a pluggable architecture for processes and data encodings. The implementation is based on the current OpenGIS specification: 05-007r7. Its focus was the creation of an extensible framework to provide algorithms for generalization on the web.
* [Baremaps](https://www.baremaps.com/) - An open source pipeline for producing Mapbox vector tiles from OpenStreetMap with Postgis and Java.
* [Deegree](http://www.deegree.org/) - Open source software for spatial data infrastructures and the geospatial web. Deegree offers components for geospatial data management, including data access, visualization, discovery and security. Open standards are at the heart of Deegree. It supports WMS, WFS for Catalogue Service, WCS, WPS, WMTS.
* [Geoserver](http://geoserver.org/) - WMS written in Java and relies on GeoTools. Allows users to share and edit geospatial data.
* [GeoTrellis Server](https://github.com/geotrellis/geotrellis-server) - Tools for building raster processing and display services. It supports WMS, WCS, WMTS and can use individual rasters, STAC Catalogs (through the STAC API service) and GeoTrellis Layers as input raster sources.
* [MapGuide](https://mapguide.osgeo.org/) - Runs on Linux or Windows, supports Apache and IIS web servers, and has APIs (PHP, .NET, Java, and JavaScript) for application development.
* [MapProxy](http://mapproxy.org/) - An open source tile server proxy for geospatial data (WMS-C, TMS, WMTS, KML SuperOverlays). It caches, accelerates and transforms data from existing map services and serves any desktop or web GIS client.
* [Mapserver](http://mapserver.org/) - WMS written in C.
* [MapTiler Server](https://www.maptiler.com/server/) - Map server for self-hosting. Publish interactive maps to get map services from your own server or laptop.
* [Nanocubes](https://github.com/laurolins/nanocube) - An in-memory data structure for spatiotemporal data cubes.
* [PGRestAPI](https://github.com/spatialdev/PGRestAPI) - Node.js REST API for PostGres Spatial Entities. AKA: SpatialServer.
* [Terracotta](https://github.com/DHI-GRAS/terracotta) - A light-weight, versatile XYZ tile server. MIT-licensed, pure Python, serving Cloud-Optimized GeoTIFF (COG).
* [THREDDS](https://github.com/Unidata/thredds) - The THREDDS Data Server (TDS) is a web server that provides metadata and data access for scientific data sets, using OPeNDAP, OGC WCS, HTTP, and other data access protocols.
* [utilery](https://github.com/tilery/utilery) - Micro vector tile manufacturing from PostGIS.
* [Zoo Project WPS](http://www.zoo-project.org/) - A WPS (Web Processing Service) implementation written in C, Python and JavaScript. It is an open source platform which implements the WPS 1.0.0 and WPS 2.0.0 standards edited by the Open Geospatial Consortium (OGC). It provides a developer-friendly framework for creating and chaining WPS compliant Web Services.


## Radar

* [GAMMA](https://www.gamma-rs.ch/software) - Allows processing of SAR, interferometric SAR (InSAR) and differential interferometric SAR (DInSAR).
* [GMT5SAR](https://topex.ucsd.edu/gmtsar/) - InSAR processing system based on GMT.
* [LiCSBAS](https://github.com/yumorishita/LiCSBAS) - LiCSBAS is an open-source package in Python and bash to carry out InSAR time series analysis using LiCSAR products.
* [NANSAT](https://github.com/nansencenter/nansat) - Nansat is a scientist friendly Python toolbox for processing 2D satellite earth observation data.
* [PolSARpro](https://earth.esa.int/web/polsarpro) - Open source radar image data processing software.
* [PyRate](https://github.com/GeoscienceAustralia/PyRate) - A Python tool for estimating velocity and time-series from Interferometric Synthetic Aperture Radar (InSAR) data.
* [pyroSAR](https://github.com/johntruckenbrodt/pyroSAR) - A Python Framework for Large-Scale SAR Satellite Data Processing.
* [PySAR](https://github.com/insarlab/PySAR) - InSAR time series analysis in Python.
* [SARbian](https://eo-college.org/sarbian/) - Free and open SAR operating system (based on Debian Linux).
* [Sarmap](https://www.sarmap.ch/index.php/software/sarscape/) - Synthetic Aperture Radar processing software.
* [SARPROZ](https://www.sarproz.com/) - Implements a wide range of Synthetic Aperture Radar (SAR), Interferometric SAR (InSAR) and Multi-Temporal InSAR processing techniques.
* [Sentinel Toolboxes](https://sentinel.esa.int/web/sentinel/toolboxes) - Free open source toolboxes for the scientific exploitation of the Sentinel missions.


## Lidar

* [CloudCompare](https://www.danielgm.net/cc/) - 3D point cloud processing software.
* [DielmoOpenLidar](http://www.dielmo.com/eng/ficha-tecnologia-software.php?prod=21) - Open source software based in gvSIG for the management of LiDAR data.
* [displaz](https://github.com/c42f/displaz) - A hackable lidar viewer.
* [Entwine](https://github.com/connormanning/entwine) - Point cloud indexing for massive datasets.
* [FullAnalyze](https://code.google.com/archive/p/fullanalyze/) - Handling, visualizing and processing lidar data (3D point clouds and waveforms).
* [Fusion](http://forsys.cfr.washington.edu/fusion/fusionlatest.html) - CLI/GUI Lidar software.
* [Global Mapper Lidar Module](https://www.bluemarblegeo.com/products/global-mapper-lidar.php) - Lidar module for Global Mapper.
* [greyhound](https://github.com/hobu/greyhound) - A point cloud streaming framework for dynamic web services and native applications.
* [Laspy](http://laspy.readthedocs.io/en/latest/) - Laspy is a python library for reading, modifying, and creating .LAS LIDAR files.
* [LAStools](http://www.cs.unc.edu/~isenburg/lastools/) - A collection of highly-efficient, scriptable tools with multi-core batching that process LAS, compressed LAZ, Terrasolid BIN, .shp, and ASCII.
* [LASzip](https://laszip.org/) - Quickly turns bulky LAS files into compact LAZ files without information loss.
* [libLAS](https://liblas.org/) - libLAS is a C/C++ library for reading and writing the very common LAS LiDAR format.
* [lidar](https://github.com/jblindsay/lidar) - A Crystal language library for reading and writing LiDAR data in LAS format.
* [lidario](https://github.com/jblindsay/lidario) - A small Go library for reading and writing LiDAR (LAS) files.
* [lidR](https://github.com/Jean-Romain/lidR) - R package for airborne LiDAR data manipulation and visualisation for forestry application.
* [MCC-LIDAR](https://sourceforge.net/projects/mcclidar/) - Multiscale Curvature Classification for LIDAR Data.
* [PDAL](http://www.pdal.io/) - PDAL is a C++ BSD library for translating and manipulating point cloud data.
* [plas.io](https://plas.io/) - WebGL point cloud rendering.
* [potree](https://github.com/potree/potree/) - Potree is a free open-source WebGL based point cloud renderer for large point clouds. PotreeConverter provides all files to view your point cloud with only a basic webserver running.
* [pyGEDI](https://github.com/EduinHSERNA/pyGEDI) - pyGEDI provides a high performance, lower cognitive load, and cleaner and more transparent code for data extraction, analysis, processing, and visualization of GEDI's products.
* [PyLAS](https://pypi.python.org/pypi/PyLAS) - A python library for reading and writing LAS files.
* [Quick Terrain Modeler](http://appliedimagery.com/) - Proprietary LiDAR exploitation software by Applied Imagery.
* [rGEDI](https://github.com/carlos-alberto-silva/rGEDI) - An R Package for NASA's Global Ecosystem Dynamics Investigation (GEDI) Data Visualization and Processing.
* [The Point Cloud Library - PCL](https://pointclouds.org/) - Standalone, large scale, open project for 2D/3D image and point cloud processing.
* [TopoDOT](https://new.certainty3d.com/) - Proprietary software for extracting topography, 3D models, GIS Assets, and more from point cloud data.
* [Treetop](https://github.com/carlos-alberto-silva/weblidar-treetop) - A Shiny-based Application for Extracting Forest Information from LiDAR data.


## 3D Application

* [3dcitybuilder](https://github.com/arthurRuf/3dcitybuilder) - QGIS Plugin that generates 3D Models of Urban Areas.
* [3dfier](https://github.com/tudelft3d/3dfier) - The open-source tool for creation of 3D models.
* [ArcGIS Earth](http://www.esri.com/software/arcgis-earth) - Display data, sketch placemarks, measure distances and areas, and add annotations at any part of the world
* [CityEngine](http://www.esri.com/software/cityengine/) - Transform 2D GIS Data into Smart 3D City Models
* [Google Earth](http://earth.google.com/) - Bringing a earth view for global mapping
* [Open3D](http://www.open3d.org/) - Open-source library that supports rapid development of software that deals with 3D data. The Open3D frontend exposes a set of carefully selected data structures and algorithms in both C++ and Python.
* [Skyline](http://www.skylineglobe.com/SkylineGlobe/corporate/Default.aspx?) - A glimpse into Skyline's cutting-edge 3D geospatial visualization products, and their potential to transform the way your organization makes decisions, shares information and manages its assets
* [World Wind](http://worldwind.arc.nasa.gov/java/) -  Providing features for displaying with geographic data

## Geographic Data Mining

* [GeoDMA](https://sourceforge.net/projects/geodma/) - GeoDMA is a plugin for TerraView software, used for geographical data mining.
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Weka is a collection of machine learning algorithms for data mining tasks written in Java.

## GNSS/INS Post Processing

* [Applanix POSPAC MMS](https://www.applanix.com/products/pospac-mms.htm) - POSPac MMS leverages Global Navigation Satellite Systems (GNSS) and inertial navigation systems (INS) data to generate a source of truth for post-mission trajectories and mapping.
* [Leica Infinity Surveying Software](https://leica-geosystems.com/en-us/products/gnss-systems/software/leica-infinity) - Easily manage and process data from multiple sites and survey teams and from all of your different survey instruments – digital levels, total stations, UAVs, GNSS sensors, and now even scanners.
* [Novatel Waypoint](https://novatel.com/products/waypoint-post-processing-software) - Waypoint software leverages Global Navigation Satellite Systems (GNSS) and inertial navigation systems (INS) data to generate a source of truth for post-mission trajectories and mapping.
* [RTKLIB](https://github.com/tomojitakasu/RTKLIB) - RTKLIB is an open source program package for standard and precise positioning
with GNSS (global navigation satellite system).
* [Trimble Business Center](https://geospatial.trimble.com/en/products/software/trimble-business-center) - Trimble® Business Center (TBC) software enables surveyors to transform field data from GNSS receivers, total stations, laser scanners, mobile mapping systems, drones and more into high-quality, actionable information and client deliverables.


## Atmospheric Correction

* [6S](http://6s.ltdri.org/) - Second Simulation of the Satellite Signal in the Solar Spectrum (6S) open source algorithm.
* [6S_emulator](https://github.com/samsammurphy/6S_emulator) - The 6S emulator is an open-source atmospheric correction tool. It is based on the 6S radiative transfer model but it runs 100x faster with minimal additional error (i.e. < 0.5 %).
* [ACOLITE_MR](https://github.com/acolite/acolite_mr) - Atmospheric correction for aquatic applications of metre-scale satellites.
* [ARCSI](https://github.com/remotesensinginfo/arcsi) - The Atmospheric and Radiometric Correction of Satellite Imagery (ARCSI) software provides a command line tool for the generation of Analysis Ready Data (ARD) optical data including atmospheric correction, cloud masking, topographic correction etc.
* [ATCOR](http://www.atcor.de/) - ERDAS Imagine module.
* [gee-atmcorr-S2](https://github.com/samsammurphy/gee-atmcorr-S2) - Atmospheric correction of Sentinel 2 imagery in Google Earth Engine using Py6S.
* [i.atcorr](https://grass.osgeo.org/grass70/manuals/i.atcorr.html) - GRASS GIS module that performs atmospheric correction using the 6S algorithm.
* [Py6S](https://py6s.readthedocs.io/en/latest/) - Py6S is a interface to the Second Simulation of the Satellite Signal in the Solar Spectrum (6S) atmospheric Radiative Transfer Model through the Python programming language.
* [radiometric_normalization](https://github.com/planetlabs/radiometric_normalization) - Implementation of radiometric normalization workflows.
* [sen2cor](http://step.esa.int/main/third-party-plugins-2/sen2cor/) - is a processor for Sentinel-2 Level 2A product generation and formatting; it performs the atmospheric-, terrain and cirrus correction of Top-Of- Atmosphere Level 1C input data.
* [SIAC](https://github.com/MarcYin/SIAC) - A sensor invariant Atmospheric Correction (SIAC).
* [SIAC_GEE](https://github.com/MarcYin/SIAC_GEE) - SIAC GEE version.


## Agent-based Modeling
* [DMASON](https://github.com/isislab-unisa/dmason) - DMASON is a parallel version of the MASON library for writing and running simulations of Agent based simulation models.
* [MASON](https://cs.gmu.edu/~eclab/projects/mason/) - MASON is a fast discrete-event multiagent simulation library core in Java, designed to be the foundation for large custom-purpose Java simulations, and also to provide more than enough functionality for many lightweight simulation needs. MASON contains both a model library and an optional suite of visualization tools in 2D and 3D.
* [Mesa](https://github.com/projectmesa/mesa) - Mesa is an Apache2 licensed agent-based modeling (or ABM) framework in Python.
* [NetLogo](https://ccl.northwestern.edu/netlogo/) - NetLogo is a multi-agent programmable modeling environment.
* [nlrx](https://github.com/ropensci/nlrx) - Provides tools to setup and execute NetLogo simulations from R.
* [Repast](https://repast.github.io/) - The Repast Suite is a family of advanced, free, and open source agent-based modeling and simulation platforms.
* [SpaDES](https://spades.predictiveecology.org/) - Metapackage for implementing a variety of event-based models, with a focus on spatially explicit models. These include raster-based, event-based, and agent-based models.


## Landscape Metrics
* [Fragstats](https://fragstats.org/) - Spatial Pattern Analysis Program for Categorical Maps.
* [landscapemetrics](https://github.com/r-spatialecology/landscapemetrics) - landscapemetrics is an R package for calculating landscape metrics for categorical landscape patterns in a tidy workflow.
* [LS_METRICS](https://github.com/LEEClab/LS_METRICS) - A tool for calculating landscape connectivity and other ecologically scaled landscape metrics
* [Makurhini](https://github.com/connectscape/Makurhini) - R package for calculating fragmentation and landscape connectivity indices used in conservation planning.
* [nlmpy](https://pypi.org/project/nlmpy/) - A Python package to create neutral landscape models.
* [NLMR](https://github.com/ropensci/NLMR) - R package to simulate neutral landscape models.
* [PyLandStats](https://github.com/martibosch/pylandstats) - An open-source Pythonic library to compute landscape metrics.


## Landscape Modelling
* [GLOBIOM](https://iiasa.ac.at/web/home/research/GLOBIOM/GLOBIOM.html) - Global Biosphere Management Model (GLOBIOM) is used to analyze the competition for land use between agriculture, forestry, and bioenergy, which are the main land-based production sectors.
* [InVEST](https://naturalcapitalproject.stanford.edu/software/invest) - InVEST (Integrated Valuation of Ecosystem Services and Tradeoffs) is a suite of models used to map and value the goods and services from nature that sustain and fulfill human life.


## Spatial Optimization
* [MARXAN](https://marxansolutions.org/) - Marxan is a freely available conservation planning software. It provides decision support to a range of conservation planning problems, including the design of new reserve systems, reporting on the performance of existing reserve systems, and developing multiple-use zoning plans for natural resource management.
* [prioriactions](https://github.com/prioriactions/prioriactions) - The prioriactions R package uses a mixed integer mathematical programming (MIP) approach for building and solving multi-action conservation planning problems, where the goal is to find an optimal combination of management actions that abate threats, in an efficient way while accounting for connectivity.
* [prioritizr](https://github.com/prioritizr/prioritizr) - R package that uses integer linear programming (ILP) techniques to provide a flexible interface for building and solving conservation planning problems.
* [Zonation](http://conservationcorridor.org/corridor-toolbox/programs-and-tools/zonation/) - Zonation produces a hierarchical prioritization of the landscape based on the occurrence levels of biodiversity features in sites (cells) by iteratively removing the least valuable remaining cell while accounting for connectivity and generalized complementarity.


## Libraries

* [GDAL](http://www.gdal.org/) - Geospatial Data Abstraction Library (GDAL) is a translator library for raster and vector geospatial data formats.
* [GeographicLib](http://geographiclib.sourceforge.net/) - For solving geodesic problems. Implemented in C, C++, Java, Javascript, Fortran, Python and Matlab.
* [Geolib](http://www.geolib.co.uk/) - GeoLib is a fast, efficient, computational geometry library available in C++, C# and Java.
* [Mapnik](http://mapnik.org/) - C++/Python/Node.js library for map rendering.
* [MDAL](https://github.com/lutraconsulting/MDAL) - Mesh Data Abstraction Library.
* [pgRouting](http://pgrouting.org/) - Extends the PostGIS / PostgreSQL geospatial database to provide geospatial routing functionality.
* [PointCloud](https://github.com/pgpointcloud/pointcloud) - A PostgreSQL extension for storing point cloud (LIDAR) data.
* [Terralib](http://www.terralib.org/) - TerraLib is a GIS classes and functions open source library.
* [TerraMA2](https://github.com/TerraMA2/terrama2) - A free and open source computational platform for early warning systems.


## PaaS - Platform as a Service

* [ArcGIS Platform](https://www.esri.com/en-us/arcgis/products/arcgis-platform/overview) - Esri's PaaS with multiple location services and developer APIs.
* [Google Maps API](https://developers.google.com/maps/) - Google's PaaS (Platform as a Service) for Geocoding or analysis/processing services.
* [Mapbox GL JS](https://www.mapbox.com/mapbox-gl-js/api/) - MapBox WebGL Javascript API.
* [Mapbox.js](https://www.mapbox.com/mapbox.js/api/v2.4.0/) - MapBox Javascript API.
* [Microsoft Bing API](https://www.microsoft.com/en-us/maps) - Microsoft Bing Maps API.
* [OpenStreetMap API](http://wiki.openstreetmap.org/wiki/API_v0.6) - OpenStreetMap API.


## SaaS - Software as a Service

* [ArcGIS Online](https://www.arcgis.com/home/) - ArcGIS Online GIS platform for mapping and spatial analysis.
* [ARLAS](https://www.arlas.io/) - ARLAS Exploration is an Open Source software for exploring and analysing Geo BigData.
* [Carto](https://carto.com/) -  Cloud computing platform that provides GIS and web mapping tools for display in a web browser.
* [CSV2GEO](https://csv2geo.com) - Batch geocoder using excel/csv file, text or API as an input and get latitude, longitude and an interactive map as output.
* [Fulcrum](http://www.fulcrumapp.com/) - A mobile data collection platform that allows you to build, deploy, & collect field data with your own customizable data collection apps.
* [GIS Cloud](https://www.giscloud.com/) - Real-time mapping platform for the entire workflow of your organization.
* [Honeycomb Maps](https://honeycombmaps.com) - Browser-based enterprise map dashboard software, with real-time filtering and metric calculation.
* [Mapbox](https://www.mapbox.com/) - Plataform for web map design and manipulation.
* [MapTiler Cloud](https://www.maptiler.com/cloud/) - Maps API for web & mobile developers. Customize maps, upload or create own geodata and publish online.
* [Mergin Maps](https://merginmaps.com/) - A mobile data collection open-source platform for field data surveys based on QGIS. Available as service or self-hosted.
* [NextGIS](http://nextgis.com/) - A cloud geospatial service that allows you to create web GIS right in the browser.
* [OpenCage Geocoding API](https://geocoder.opencagedata.com/) - An API aggregating multiple open geo datasources (OpenStreetMap and others).
* [OpenMapTiles](https://openmaptiles.com/) - Vector tiles and map services as service, self-hosted or off-line.
* [Geobox](https://en.geobox.ir/) - Geobox is a suite of products that together cover all stages of building an online GIS.


## DaaS - Data as a Service

* [Apple Maps](https://mapsconnect.apple.com/) - Apple map service.
* [Google Maps](https://www.google.com.br/maps) - Google map service.
* [Microsoft Bing Maps](http://www.bing.com/mapspreview) - Microsoft map service.
* [OpenStreetMap](http://www.openstreetmap.org/) - OpenStreeMap map service.


## Google Earth Engine

* [AREA2](https://area2.readthedocs.io/en/latest/overview.html) - AREA 2 (“area squared” or “area two”), short for Area Estimation & Accuracy Assessment, is a Google Earth Engine application that provides comprehensive support for sampling and estimation in a design-based inference framework.
* [BAP-GEE](https://github.com/saveriofrancini/bap) - Best Available Pixel calculation using Google Earth Engine.
* [earthEngineGrabR](https://github.com/JesJehle/earthEngineGrabR) - The earthEngineGrabR is an interface between R and the Google Earth Engine, which simplifies the acquisition of remote sensing data.
* [EarthEngine.jl](https://github.com/KMarkert/EarthEngine.jl) - Google Earth Engine in Julia.
* [ee-fastapi](https://github.com/csaybar/ee-fastapi) - Flood Detection with Google Earth Engine.
* [ee-goes](https://github.com/jdbcode/ee-goes) - An Earth Engine JavaScript library for visualizing GOES-R time series.
* [ee-rgb-timeseries](https://github.com/jdbcode/ee-rgb-timeseries) - Earth Engine JS module to color time series chart points as stretched 3-band RGB.
* [eemont](https://github.com/davemlz/eemont) - A python package that extends Google Earth Engine.
* [exploreRGEE](https://github.com/joshualerickson/exploreRGEE) - Google Earth Engine (GEE) in the Rstudio IDE.
* [gee-atmcorr-S2](https://github.com/samsammurphy/gee-atmcorr-S2) - Atmospheric correction of Sentinel 2 imagery in Google Earth Engine using Py6S.
* [geemap](https://github.com/giswqs/geemap) - A Python package for interactive mapping with Google Earth Engine, ipyleaflet, and ipywidgets.
* [gee_s1_ard](https://github.com/adugnag/gee_s1_ard) - Creates an analysis ready sentinel-1 SAR image collection in Google Earth Engine by applying additional border noise correction, speckle filtering and radiometric terrain normalization.
* [GEET](https://github.com/sacridini/GEET) - Google Earth Engine Toolbox - Library to write small EE apps or big/complex apps with a lot less code.
* [geeup](https://github.com/samapriya/geeup) - Simple CLI for Earth Engine Uploads.
* [landsat-extract-gee](https://github.com/loicdtx/landsat-extract-gee) - Get Landsat surface reflectance time-series from google earth engine.
* [msslib](https://github.com/gee-community/msslib) - An Earth Engine JavaScript library for working with Landsat MSS image data.
* [OEEex](https://github.com/open-geocomputing/OEEex) - A chrome extension to enhance Google Earth Engine code editor.
* [OpenEarthEngineLibrary](https://github.com/open-geocomputing/OpenEarthEngineLibrary) - Collection of code goodies for Google Earth Engine(GEE).
* [restee](https://kmarkert.github.io/restee/) - Aims to make plugging Earth Engine (EE) computations into downstream Python processing easier.
* [rgee](https://github.com/r-spatial/rgee) - Google Earth Engine for R.
* [sankee](https://github.com/aazuspan/sankee) - Visualize classified time series data with interactive Sankey plots in Google Earth Engine.
* [spectral](https://github.com/awesome-spectral-indices/spectral) - Awesome Spectral Indices for the Google Earth Engine JavaScript API (Code Editor).
* [wxee](https://github.com/aazuspan/wxee) - A Python interface between Earth Engine and xarray for processing weather and climate data.


## Deep Learning

* [AIDE](https://github.com/microsoft/aerial_wildlife_detection) - Annotation Interface for Data-driven Ecology: Tools for detecting wildlife in aerial images using active learning
* [AirNet](https://github.com/mathildor/TF-SegNet) - SegNet-like network implemented in TensorFlow to use for segmenting aerial images.
* [Deep Learning ArcGIS](https://github.com/Esri/deep-learning-frameworks) - Deep Learning Libraries Installers for ArcGIS.
* [DeepForest](https://github.com/weecology/DeepForest) - Python Package for Tree Crown Detection in Airborne RGB imagery.
* [eo-learn](https://github.com/sentinel-hub/eo-learn) - Earth observation processing framework for machine learning in Python.
* [Hyperspectral](https://github.com/KGPML/Hyperspectral) - Deep Learning for Land-cover Classification in Hyperspectral Images.
* [Label Maker](https://github.com/developmentseed/label-maker) - Data Preparation for Satellite Machine Learning.
* [libtorch-yolov3](https://github.com/walktree/libtorch-yolov3) - A Libtorch implementation of the YOLO v3 object detection algorithm.
* [LightNet](https://github.com/ansleliu/LightNet) - LightNet: Light-weight Networks for Semantic Image Segmentation (Cityscapes and Mapillary Vistas Dataset)
* [mmsegmentation](https://github.com/open-mmlab/mmsegmentation) - MMSegmentation is an open source semantic segmentation toolbox based on PyTorch. It is a part of the OpenMMLab project.
* [Pixel Decoder](https://github.com/Geoyi/pixel-decoder) - A machine learning python package to run deep learning with satellite imagery.
* [PixelLib](https://github.com/ayoolaolafenwa/PixelLib) - Pixellib is a library for performing segmentation of images. It suports both Semantic Segmentation as Instance Segmentation.
* [platypus](https://github.com/maju116/platypus) - R package for object detection and image segmentation.
* [Presto](https://github.com/nasaharvest/presto) - Lightweight, Pre-trained Transformers for Remote Sensing Timeseries.
* [Raster Vision](https://github.com/azavea/raster-vision) - An open source framework for deep learning on satellite and aerial imagery.
* [SamGIS](https://github.com/trincadev/samgis-be) – Image Segmentation machine learning based (Segment Anything by Meta - Facebook) applied to GIS and geo data also with GPU requirements. A Segment Anything HuggingFace demo [here](https://huggingface.co/spaces/aletrn/samgis) and an HuggingFace [demo](https://huggingface.co/spaces/aletrn/samgis-lisa-on-cuda) with natural language-based image segmentation capabilities via [LISA](https://github.com/dvlab-research/LISA).
* [segment-geospatial](https://github.com/opengeos/segment-geospatial) - Meta AI' Segment Anything Model (SAM) for Geospatial Data
* [sentinel-tree-cover](https://github.com/wri/sentinel-tree-cover) - Image segmentations of trees outside forest.
* [ShelfNet](https://github.com/juntang-zhuang/ShelfNet) - Implementation of a CNN model for real-time semantic segmentation.
* [SIMRDWN](https://github.com/avanetten/simrdwn) - The Satellite Imagery Multiscale Rapid Detection with Windowed Networks (SIMRDWN) codebase combines some of the leading object detection algorithms into a unified framework designed to detect objects both large and small in overhead imagery.
* [SNIPER](https://github.com/mahyarnajibi/SNIPER) - SNIPER is an efficient multi-scale object detection algorithm.
* [Solaris](https://github.com/cosmiq/solaris) - CosmiQ Works Geospatial Machine Learning Analysis Toolkit.
* [srcnn](https://github.com/WarrenGreen/srcnn) - Super Resolution for Satellite Imagery.
* [Temporal Convolutional Neural Network](https://github.com/charlotte-pel/temporalCNN) - Temporal Convolutional Neural Network for the Classification of Satellite Image Time Series.
* [TernausNetV2](https://github.com/ternaus/TernausNetV2) - TernausNetV2: Fully Convolutional Network for Instance Segmentation.
* [TorchGeo](https://github.com/microsoft/torchgeo) - TorchGeo is a PyTorch domain library, similar to torchvision, that provides datasets, transforms, samplers, and pre-trained models specific to geospatial data.
* [TorchSat](https://github.com/sshuair/torchsat) - TorchSat is an open-source PyTorch framework for satellite imagery analysis.
* [tsl](https://github.com/TorchSpatiotemporal/tsl) - PyTorch library for processing spatiotemporal data.
* [WaterNet](https://github.com/treigerm/WaterNet) - A convolutional neural network that identifies water in satellite images.
* [YOLT](https://github.com/avanetten/yolt) - You Only Look Twice: Rapid Multi-Scale Object Detection In Satellite Imagery.

## C

* [Datamaps](https://github.com/ericfischer/datamaps) - This is a tool for indexing large lists of geographic points or lines and dynamically generating map tiles from the index for display.
* [FORCE](https://github.com/davidfrantz/force) - Framework for Operational Radiometric Correction for Environmental monitoring.
* [H3](https://github.com/uber/h3) - Hexagonal hierarchical geospatial indexing system.
* [libpostal](https://github.com/openvenues/libpostal) - A C library for parsing/normalizing street addresses around the world. Powered by statistical NLP and open geo data.
* [libvips](https://github.com/libvips/libvips) - A fast image processing library with low memory needs.
* [Shapefile C Library](http://shapelib.maptools.org/) - Provides the ability to write simple C programs for reading, writing and updating (to a limited extent) .shp and .dbf files.
* [udunits2](https://github.com/Unidata/UDUNITS-2) - API and utility for arithmetic manipulation of units of physical quantities.
* [YOLT](https://github.com/CosmiQ/yolt) - You Only Look Twice: Rapid Multi-Scale Object Detection In Satellite Imagery.

## C++

* [Boost Geometry](http://www.boost.org/doc/libs/1_61_0/libs/geometry/doc/html/index.html) - Part of collection of the Boost C++ Libraries, defines concepts, primitives and algorithms for solving geometry problems.
* [Capaware](https://en.wikipedia.org/wiki/Capaware) - 3D terrain representation with multilayer representation.
* [copc-lib](https://github.com/RockRobotic/copc-lib) - copc-lib provides an easy-to-use interface for reading and creating Cloud Optimized Point Clouds.
* [cpd](https://github.com/gadomski/cpd) - Coherent Point Drift (CPD) is a point-set registration algorithm.
* [depthmapX](https://github.com/varoudis/depthmapX) - Multi-platform Spatial Network Analysis Software.
* [dreich_algorithm](https://github.com/csdms-contrib/dreich_algorithm) - Algorithm for extracting channel networks from high resolution topographic data.
* [entwine](https://github.com/connormanning/entwine) - Entwine is a data organization library for massive point clouds, designed to conquer datasets of hundreds of billions of points as well as desktop-scale point clouds.
* [GDAL](http://www.gdal.org/) - Geospatial Data Abstraction Library (GDAL) is a computer library that serve as a translator library for raster and vector geospatial data formats.
* [gdalcubes](https://github.com/appelmar/gdalcubes) - gdalcubes is a library to represent collections of Earth Observation (EO) images as on demand data cubes (or multidimensional arrays).
* [geojson-vt-cpp](https://github.com/mapbox/geojson-vt-cpp) - Port to C++ of JS GeoJSON-VT for slicing GeoJSON into vector tiles on the fly.
* [GEOS](https://trac.osgeo.org/geos/) - GEOS (Geometry Engine - Open Source) is a C++ port of the Java Topology Suite (JTS).
* [gSLICr](https://github.com/carlren/gSLICr) - Real-time super-pixel segmentation.
* [Halide](https://github.com/halide/Halide) - Halide is a programming language designed to make it easier to write high-performance image processing code on modern machines.
* [hmm](https://github.com/fogleman/hmm) - Heightmap meshing utility
* [hydroflow](https://github.com/sistemalabgis/hydroflow) - Compute drainage orders in drainage basins using Strahler and Shreve methods.
* [ITK](https://itk.org/) - ITK is an open-source, cross-platform system that provides developers with an extensive suite of software tools for image analysis.
* [LASzip](https://github.com/LASzip/LASzip) - Quickly turns bulky LAS files into compact LAZ files without information loss.
* [laz-perf](https://github.com/hobu/laz-perf) - Alternative LAZ implementation for C++ and JavaScript.
* [libGeoTiff](https://trac.osgeo.org/geotiff/) - Manipulate TIFF based interchange format for georeferenced raster imagery.
* [libspatialindex](https://github.com/libspatialindex/libspatialindex) - C++ implementation of R*-tree, an MVR-tree and a TPR-tree with C API.
* [Mapbox GL Native](https://github.com/mapbox/mapbox-gl-native) - Render Mapbox styles in mobile, desktop, and node applications using C++ and OpenGL.
* [Mapbox Maps SDK for Qt](https://www.mapbox.com/qt/) - Qt Automotive Map Suite.
* [Mapnik Vector Tile](https://github.com/mapbox/mapnik-vector-tile) - Mapnik C++ implemention of Mapbox Vector Tile specification.
* [Mapnik](http://mapnik.org/) - C++ library for map rendering.
* [Mapzen Tangram-ES](https://github.com/tangrams/tangram-es) - C++ library for rendering 2D and 3D maps using OpenGL ES 2 with custom styling and interactions
* [networkit](https://github.com/networkit/networkit) - NetworKit is a growing open-source toolkit for large-scale network analysis.
* [OpenDroneMap](https://github.com/OpenDroneMap/OpenDroneMap) - OpenDroneMap is a tool to postprocess drone, balloon, kite, and street view data to geographic data including orthophotos, point clouds, & textured mesh.
* [OpenOrienteering Mapper](https://github.com/OpenOrienteering/mapper) - OpenOrienteering Mapper is a software for creating maps for the orienteering sport.
* [Orfeo ToolBox](https://www.orfeo-toolbox.org/) - Orfeo TooLBox (OTB) is an open-source C++ library for remote sensing images processing, distributed under the Apache v2.0 licence.
* [osgearth](https://github.com/gwaldron/osgearth) - A free open source C++ geospatial toolkit.
* [OSMExpress](https://github.com/protomaps/OSMExpress) - Fast database file format for OpenStreetMap.
* [OSRM (Open Source Routing Machine)](http://project-osrm.org/) - High performance routing engine written in C++, designed to run on OpenStreetMap data. Services available: Nearest, Route, Table, Match, Trip, Tile.
* [otbtf](https://github.com/remicres/otbtf) - Deep learning with otb.
* [pprepair](https://github.com/tudelft3d/pprepair) - Validation and Automatic Repair of Planar Partitions.
* [prepair](https://github.com/tudelft3d/prepair) - Automatic repair of single polygons (according to the OGC Simple Features / ISO19107 rules) using a constrained triangulation.
* [Pronto Raster](https://github.com/ahhz/raster) - C++ library for geographical raster data analysis.
* [RichDEM](https://github.com/r-barnes/richdem) - High-performance Terrain and Hydrology Analysis.
* [RoutingKit](https://github.com/RoutingKit/RoutingKit) - RoutingKit is a C++ library that provides advanced route planning functionality.
* [RSGISLib](http://rsgislib.org/) - The Remote Sensing and GIS software library (RSGISLib) is a collection of tools for processing remote sensing and GIS datasets. The tools are accessed using Python bindings or an XML interface.
* [S2 Geometry](https://github.com/google/s2geometry) - Computational geometry and spatial indexing on the sphere.
* [Selene](https://github.com/kmhofmann/selene) - A C++14 image representation, processing and I/O library.
* [Spatial](https://sourceforge.net/projects/spatial/) - Spatial is a generic header-only C++ library providing multi-dimensional in-memory containers, iterators and functionals.
* [Supercluster](https://github.com/mapbox/supercluster.hpp) - A C++14 port of supercluster, a fast 2D point clustering library for use in interactive maps.
* [TauDEM](https://github.com/dtarb/TauDEM) - Terrain Analysis Using Digital Elevation Models (TauDEM) software for hydrologic terrain analysis and channel network extraction.
* [Terralib](http://www.dpi.inpe.br/terralib5/wiki/doku.php?id=start) - TerraLib is a GIS classes and functions open source library.
* [TIN Terrain](https://github.com/heremaps/tin-terrain) - A command-line tool for converting heightmaps in GeoTIFF format into tiled optimized meshes.
* [tippecanoe](https://github.com/mapbox/tippecanoe) - Build vector tilesets from large collections of GeoJSON features.
* [valhalla](https://github.com/valhalla/valhalla) - Open Source Routing Engine for OpenStreetMap.
* [Vector Tiles Producer](https://github.com/vross/vector-tiles-producer) - Command line tool in C++ to creates vector tiles for a given area at chosen zoom levels using a Mapnik XML.
* [VROOM](https://github.com/VROOM-Project/vroom) - VROOM is an open-source optimization engine written in C++17 that aim at providing good solutions to various real-life vehicle routing problems (VRP) within a small computing time.

## C Sharp
* [ArcBruTile](https://github.com/ArcBruTile/ArcBruTile) - ArcBruTile displays a collection of maps in ArcGIS Pro 2.0 and ArcMap 10.0 - 10.6.
* [AzureMapsRestServices](https://github.com/perfahlen/AzureMapsRestServices) - .Net Standard 2.0 library to access AzureMaps Services.
* [Bing Maps REST Toolkit](https://github.com/Microsoft/BingMapsRESTToolkit) - This is a portable class library which makes it easy to access the Bing Maps REST services from .NET.
* [Bing Maps Spatial Data Services Toolkit](https://github.com/Microsoft/BingMapsSDSToolkit) - This toolkit makes it easy to use the Bing Maps Spatial Data Services (SDS) in .NET.
* [Bing Maps WPF SDK ](https://msdn.microsoft.com/en-us/library/hh750210.aspx) - The Bing Maps WPF API.
* [Bing-Maps-Fleet-Tracker](https://github.com/Microsoft/Bing-Maps-Fleet-Tracker) - The Bing Maps Fleet Tracker is a tracking solution for small to medium sized teams. Easily track vehicles and mobile devices.
* [BotBuild-Location](https://github.com/Microsoft/BotBuilder-Location) - An open-source location picker control for Microsoft Bot Framework powered by Bing Maps REST services.
* [BruTile](https://github.com/BruTile/BruTile) - BruTile is a .NET library to access tile services like those of OpenStreetMap, MapBox or GeodanMaps.
* [DEM Net Elevation API](https://github.com/dem-net/DEM.Net) - 3D terrain generation library, provides access to global DEM datasets (OpenTopography, Nasa ASTER) and tiled imagery services. GlTF and STL export formats supported. [Live demo](https://elevationapi.com)
* [DotSpatial](https://github.com/DotSpatial/DotSpatial) - DotSpatial is a geographic information system library written for .NET 4.
* [Earth-Lens](https://github.com/Microsoft/Earth-Lens) - Earth Lens, a Microsoft Garage project is an iOS iPad application that helps people and organizations quickly identify and classify objects in aerial imagery through the power of machine learning.
* [GDAL/OGR CSharp](https://trac.osgeo.org/gdal/wiki/GdalOgrInCsharp) - C# bindings for GDAL and OGR.
* [Geo](https://github.com/sibartlett/Geo) - A geospatial library for .NET
* [GeoJSON.Net](https://github.com/GeoJSON-Net/GeoJSON.Net) - .Net library for GeoJSON types & corresponding Json.Net (de)serializers.
* [GeoJSON4EntityFramework](https://github.com/alatas/GeoJSON4EntityFramework) - Create GeoJSON from Entity Framework Spatial Data or WKT.
* [Mapbox Maps SDK for Unity](https://www.mapbox.com/unity-sdk/) - The Maps SDK for Unity is a collection of tools for building Unity applications from real map data.
* [MaxRev.Gdal.Core](https://github.com/MaxRev-Dev/gdal.netcore) - Bindings for GDAL and OGR (both win-x64 and linux-x64).
* [NTS Net Topology Suite](https://github.com/NetTopologySuite/NetTopologySuite) - A .NET GIS solution that is fast and reliable for the .NET platform.
* [osmsharp](http://www.osmsharp.com/) - OsmSharp is a C# library to work with OpenStreetMap (OSM) data.
* [Sanchez](https://github.com/nullpainter/sanchez) - False-colour geostationary satellite image compositor.
* [SharpKml](https://github.com/samcragg/sharpkml) - Is able to read/write both KML files and KMZ files.
* [SharpMap](https://github.com/SharpMap/SharpMap) - SharpMap is an easy-to-use mapping library for use in web and desktop applications.
* [Windows UWP map control](https://msdn.microsoft.com/en-us/library/windows/apps/xaml/dn642089.aspx) - The Bing Maps control built into the Windows UWP platform.

## Clojure

* [geo](https://github.com/Factual/geo) - Clojure library for working with geohashes, polygons, and other world geometry.


## Crystal

* [lidar](https://github.com/jblindsay/lidar) - A Crystal language library for reading and writing LiDAR data in LAS format.

## CSS

* [CartoCSS](https://www.mapbox.com/tilemill/docs/manual/carto/) - TileMills language.
* [MapCSS](http://wiki.openstreetmap.org/wiki/MapCSS) - MapCSS is a CSS-like language for map stylesheets.

## Dart

* [turf_dart](https://github.com/dartclub/turf_dart) - A turf.js-like geospatial analysis library working with GeoJSON, written in pure Dart.

## Delphi

* [DSpatial](http://dspatial.sourceforge.net/) - DSpatial is an Open Source software development project to provide developers using Delphi with a library of tools for the use, manipulation, and visualization of spatial data.

## Elixir

* [distance](https://github.com/pkinney/distance) - Provides a set of distance functions for use in GIS or graphic applications.
* [geo](https://github.com/bryanjos/geo) - A collection of GIS functions for Elixir.
* [Geometry Library](https://github.com/pkinney/topo) - A Geometry library for Elixir that calculates spatial relationships between two geometries.
* [GeoPostGIS](https://github.com/bryanjos/geo_postgis) - Postgrex extension for the PostGIS data types.

## Fortran
* [6S](http://6s.ltdri.org/) - Second Simulation of the Satellite Signal in the Solar Spectrum (6S) open source algorithm.
* [SPECFEM3D_GLOBE](https://github.com/geodynamics/specfem3d_globe) - SPECFEM3D_GLOBE simulates global and regional (continental-scale) seismic wave propagation.
* [SWAT](https://github.com/WatershedModels/SWAT) - Implementation of SWAT model.

## Go

* [BoxTree](https://github.com/tidwall/boxtree) - An R-tree implementation for Go.
* [BuntDB](https://github.com/tidwall/buntdb) - BuntDB is an embeddable, in-memory key/value database for Go with custom indexing and geospatial support.
* [cogger](https://github.com/airbusgeo/cogger) - cogger is a fast geotiff to COG converter.
* [Draw2D](https://github.com/llgcode/draw2d) - 2D rendering for different output (raster, pdf).
* [geom](https://github.com/ctessum/geom) - Geometry objects and functions for Go.
* [Go GDAL](https://github.com/lukeroth/gdal) - Go (golang) wrapper for GDAL, the Geospatial Data Abstraction Library.
* [go-geom](https://github.com/twpayne/go-geom) - Go library for handling geometries.
* [Go-proj-4](https://github.com/pebbe/go-proj-4) - Go bindings for the Cartographic Projections Library PROJ.4.
* [Go-shp](https://github.com/jonas-p/go-shp) - Go library for reading and writing ESRI Shapefiles. Pure Golang implementation based on the ESRI Shapefile technical description.
* [go-spatial](https://github.com/jblindsay/go-spatial) - GoSpatial is a simple command-line interface program for manipulating geospatial data.
* [godal](https://github.com/airbusgeo/godal) - Godal aims at providing an idiomatic go wrapper around the GDAL library.
* [gopostal](https://github.com/openvenues/gopostal) - Go (cgo) interface to libpostal for fast international address parsing/normalization.
* [GoSpatial](https://github.com/jblindsay/go-spatial) - GoSpatial is a simple command-line interface program for manipulating geospatial data.
* [lidario](https://github.com/jblindsay/lidario) - A small Go library for reading and writing LiDAR (LAS) files.
* [orb](https://github.com/paulmach/orb) - A set of types for working with 2d geo and planar/projected geometric data in Golang
* [pg_featureserv](https://github.com/CrunchyData/pg_featureserv) - Lightweight RESTful Geospatial Feature Server for PostGIS in Go.
* [pg_tileserv](https://github.com/CrunchyData/pg_tileserv) - A very thin PostGIS-only tile server in Go. Takes in HTTP tile requests, executes SQL, returns MVT tiles.
* [S2](https://github.com/golang/geo) - S2 is a library for spherical geometry that aims to have the same robustness, flexibility, and performance as the best planar geometry libraries.
* [Tegola](https://github.com/go-spatial/tegola) - Tegola is a vector tile server delivering Mapbox Vector Tiles with support for PostGIS and GeoPackage data providers.

## Groovy

* [GeoScript Groovy](https://github.com/geoscript/geoscript-groovy) - GeoScript Groovy is the Groovy implementation of GeoScript.

## Haskell

* [HGeometry](https://github.com/noinia/hgeometry) - HGeometry is a library for computing with geometric objects in Haskell. It defines basic geometric types and primitives, and it implements some geometric data structures and algorithms.
* [hgis](https://hackage.haskell.org/package/hgis) - Package containing functions to make graphs, read shapefiles, and compute areas/perimeters of geographic features.
* [Naqsha](https://github.com/naqsha/naqsha) - Naqsha is a Haskell library to work with geospatial data types.
* [TerraHS](https://wiki.haskell.org/TerraHS) - TerraHS is a software component that enables the development of geographical applications in a functional language, using the data handling capabilities and spatial operations of TerraLib.
## IDL

* [LandTrendr](https://github.com/KennedyResearch/LandTrendr-2012) - LandTrendr (Landsat-based Detection of Trends in Disturbance and Recovery) attempt to capture, label, and map changes in Earth's surface for use in science, natural resource management, and education.

## Java

* [Apache SIS](http://sis.apache.org/) - Apache Spatial Information System (SIS) is a free software, Java language library for developing geospatial applications.
* [asgbook](https://github.com/lakshmanok/asgbook) - Implementation of GIS/RS features in Java. Its also the code accompanying the book "Automating the Analysis of Spatial Grids" by Valliappa Lakshmanan.
* [GDAL Warp Bindings](https://github.com/geotrellis/gdal-warp-bindings) - Thread-safe bindings for GDAL's Warp functionality.
* [Geoapi](http://www.geoapi.org/) - GeoAPI provides a set of Java language programming interfaces for geospatial applications.
* [Geo Assist](https://github.com/thegeekyasian/geo-assist) - Geo Assist is an open source API for indexing and querying spatial data in the most efficient manner. It allows you to store 2D spatial data in-memory and support features such as find nearest neighbors, find in bounding box, etc.
* [Geonetwork](http://geonetwork-opensource.org/) - GeoNetwork is a catalog application to manage spatially referenced resources.
* [GeoServer](http://geoserver.org/) - GeoServer is open source server for sharing geospatial data.
* [Geotools](http://www.geotools.org/) - GeoTools is an open source Java library that provides tools for geospatial data.
* [GeoWebCache](http://www.geowebcache.org/) - a Java web application used to cache map tiles coming from a variety of sources such as OGC Web Map Service (WMS). It implements various service interfaces (such as WMS-C, WMTS, TMS, Google Maps KML, Virtual Earth) in order to accelerate and optimize map image delivery. It can also recombine tiles to work with regular WMS clients.
* [GeOxygene](https://sourceforge.net/projects/oxygene-project/) - Provide an open framework which implements OGC/ISO specifications for the development and deployment of GIS applications.
* [Gisgraphy](http://www.gisgraphy.com/) - Open source framework that offers the ability to do geolocalisation and geocoding via Java APIs or REST webservices.
* [GraphHopper Routing Engine](https://github.com/graphhopper/graphhopper) - GraphHopper is a fast and memory efficient Java routing engine, released under Apache License 2.0. By default it uses OpenStreetMap and GTFS data, but it can import other data sources.
* [JGeocoder](http://jgeocoder.sourceforge.net/) - Free Java Geocoder.
* [jpostal](https://github.com/openvenues/jpostal) - Java/JNI bindings to libpostal for fast international street address parsing/normalization.
* [JTS Topology Suite](https://github.com/locationtech/jts) - JTS Topology Suite is an API of 2D spatial predicates and functions.
* [LuciadLightspeed](http://www.luciad.com/solutions/luciadlightspeed) - A Java library that provides the foundations for advanced geospatial analytics applications
* [MapFish Print](https://mapfish.github.io/mapfish-print-doc/) - The purpose of Mapfish Print is to create reports that contain maps (and map related components) within them. The project is a Java based servlet/library/application based on the mature Jasper Reports Library.
* [Openmap](https://github.com/openmap-java/openmap) - Open Source JavaBeans-based programmer's toolkit.
* [PDAL-Java](https://github.com/PDAL/java) - Java extension and bindings for PDAL.
* [Photon](https://github.com/komoot/photon) - Photon is an open source geocoder built for OpenStreetMap data. It is based on elasticsearch.
* [Proj4j](https://github.com/locationtech/proj4j) - Java port of the Proj.4 library for coordinate reprojection.
* [Spatial4j](https://github.com/locationtech/spatial4j) - Spatial4j is a general purpose geospatial ASL licensed open-source Java library.
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Weka is a collection of machine learning algorithms for data mining tasks written in Java.
* [World Wind Java SDK](http://worldwind.arc.nasa.gov/java/) - Nasa cross-platform Java SDK.

## JavaScript
* [Arabesque](https://github.com/gflowiz/arabesque) - Arabesque is a web application for thematic mapping of flow and networks datasets.
* [arc.js](https://github.com/springmeyer/arc.js) - Calculate great circles routes as lines in GeoJSON or WKT format.
* [ArcGIS Maps SDK for JavaScript](https://developers.arcgis.com/javascript/) - ArcGIS Maps SDK for JavaScript is a proprietary toolkit that enables developers to build web-based mapping and spatial analysis applications that integrate with the ArcGIS ecosystem.
* [Bing Maps V8 Code Samples](https://github.com/Microsoft/BingMapsV8CodeSamples) - A large collection of open source code samples for Bing Maps V8.
* [Bing Maps V8 Interactive SDK](https://www.bing.com/api/maps/sdkrelease/mapcontrol/isdk#loadMapWithOptions+JS) - An interactive code sample gallery for Bing Maps V8.
* [Bing Maps V8 TypeScript Definitions ](https://github.com/Microsoft/Bing-Maps-V8-TypeScript-Definitions) - TypeScript Definitions for the Bing Maps V8 web control.
* [Bing Maps V8 Web Control](https://msdn.microsoft.com/en-us/library/mt712542.aspx) - Bing Maps API for JavaScript.
* [Bertin.js](https://github.com/neocarto/bertin) - A JavaScript library for visualizing geospatial data and make thematic maps for the web.
* [CesiumJS](https://github.com/AnalyticalGraphicsInc/cesium) - An open-source JavaScript library for world-class 3D globes and maps.
* [d3-geomap](https://d3-geomap.github.io/) - A library for creating geographical maps based on D3.js.
* [de9im](https://github.com/dpmcmlxxvi/de9im) - A collection of fast functions for DE-9IM spatial operations.
* [deck.gl](https://github.com/uber/deck.gl) - WebGL2 powered geospatial visualization layers.
* [eurostat-map.js](https://github.com/eurostat/eurostat-map.js) - Reusable library to quickly create and customise web maps showing Eurostat data directly retrieved from Eurostat database.
* [Galton](https://github.com/urbica/galton) - Lightweight Node.js isochrone server. Build isochrones using OSRM, Turf and concaveman.
* [gdal-js](https://github.com/ddohler/gdal-js/) - An Emscripten port of GDAL 2.1.
* [geoblaze](https://github.com/GeoTIFF/geoblaze) - Geoblaze is a geospatial raster processing engine written purely in javascript.
* [Geodesy](https://github.com/chrisveness/geodesy) - Libraries of geodesy functions implemented in JavaScript.
* [GeoExt](https://geoext.github.io/geoext3/) - Open Source and enables building desktop-like GIS applications through the web. It is a JavaScript framework that combines the GIS functionality of OpenLayers with the user interface of the ExtJS library provided by Sencha.
* [geojson-merge](https://github.com/mapbox/geojson-merge) - Merge multiple GeoJSON files into one FeatureCollection.
* [Geokit](https://github.com/developmentseed/geokit) - Geokit is a command-line interface (CLI) tool written in javascript, that contains all the basic functionalities for measurements, conversions and operations of geojson files.
* [geoverview ](https://github.com/neocarto/geoverview) - Based on maplibre-gl, geoverview is a tool for giving a quick and easy geographic overview of any geojson (and the information it contains).
* [GeoPackage.js](https://github.com/ngageoint/geopackage-js) - GeoPackage JS is an implementation of the OGC GeoPackage spec. This library works in both the browser and Node 4+.
* [geopouch](https://github.com/pouchdb/geopouch) - Spatial plugin from PouchDB extracted and supporting N dimensional coordinates.
* [Geo-Three](https://github.com/tentone/geo-three) - Tile based geographic world map visualization library for threejs.
* [geotiff.js](https://github.com/geotiffjs/geotiff.js) - geotiff.js is a small library to parse TIFF files for visualization or analysis.
* [geotoolbox](https://github.com/neocarto/geotoolbox) - is javascript tool for geographers. It allows to simply deal with geojson properties (attribute data) and provides several GIS operations useful for thematic cartography.
* [Ginkgoch](https://ginkgoch.com) - Ginkgoch is a GIS visualization, analyze library on Node.js. It allows to build cross-platform GIS services, desktop and mobile apps.
* [gmaps.js](https://github.com/hpneo/gmaps) - gmaps.js allows you to use the potential of Google Maps in a simple way.
* [Google Maps API](https://developers.google.com/maps/documentation/javascript/?hl=pt-br) - Google Maps API for JavaScript.
* [Heatcanvas.js](https://github.com/sunng87/heatcanvas) - Yet another heatmap implementation for Javascript.
* [Heatmap.js](https://www.patrick-wied.at/static/heatmapjs/) - A heatmap implementation for Javascript.
* [hyperleaflet](https://hyperleaflet.dev/) - A library that allows you to use the popular Leaflet library with just HTML attributes.
* [iTowns](http://www.itowns-project.org/) - A Three.js-based framework written in Javascript/WebGL for visualizing 3D geospatial data. It can connect to WMS/WMTS/TMS servers including elevation data and load many different data formats (3dTiles, gpx, KML and much much more).
* [JSTS](https://github.com/bjornharrtell/jsts) - Port of the Java JTS library.
* [jVectorMap](https://jvectormap.com/) - jVectorMap is a vector-based, cross-browser and cross-platform component for interactive geography-related data visualization on the web. It provides numerious features like smooth zooming and panning, fully-customizable styling, markers, labels and tooltips.
* [kepler.gl](https://kepler.gl/) - kepler.gl is a data-agnostic, high-performance web-based application for visual exploration of large-scale geolocation data sets.
* [Koop](https://koopjs.github.io/) - An open source geospatial data server. Transform geospatial data on the fly and serve as GeoJSON, Vector Tiles, Feature Services and more.
* [landsat8.earth](https://github.com/kylebarron/landsat8.earth) - 2D/3D WebGL-powered Landsat 8 satellite imagery analysis.
* [landspeed.js](https://github.com/springmeyer/landspeed.js) - WMS server using node-mapnik.
* [leaflet](http://leafletjs.com/) - Open-Source JavaScript Library for Mobile-Friendly Interactive Maps.
* [leaflet-elevation](https://github.com/Raruto/leaflet-elevation) - Leaflet plugin that allows to add elevation profiles using d3js
* [leaflet-providers](https://github.com/leaflet-extras/leaflet-providers) - An extension to Leaflet that contains configurations for various free tile providers.
* [leaflet TimeDimension](https://github.com/socib/Leaflet.TimeDimension) - Add time dimension capabilities on a Leaflet map.
* [Loam](https://github.com/azavea/loam) - Javascript wrapper for GDAL in the browser.
* [LuciadRIA](http://www.luciad.com/solutions/luciadria) - A JavaScript library for 3D globes and maps, with support for military symbology and desktop-like performance
* [mapbox-gl-draw](https://github.com/mapbox/mapbox-gl-draw) - Draw tools for mapbox-gl-js.
* [mapboxgl-powerbi](https://github.com/mapbox/mapboxgl-powerbi) - Mapbox GL PowerBI custom visual.
* [mapshaper-proj](https://github.com/mbloch/mapshaper-proj) - A JavaScript port of the Proj.4 map projection library.
* [NASA WebWorldWind](https://github.com/NASAWorldWind/WebWorldWind) - The NASA WorldWind Javascript SDK (WebWW) includes the library and examples for creating geo-browser web applications and for embedding a 3D globe in HTML5 web pages.
* [openaq](https://github.com/nickolasclarke/openaq) - A JS client for the OpenAQ API. OpenAQ is a non-profit organization empowering communities around the globe to clean their air by harmonizing, sharing, and using open air quality data.
* [OpenGlobus](https://www.openglobus.org/) - A javascript library designed to display interactive 3d maps and planets with map tiles, imagery and vector data, markers and 3d objects. It uses the WebGL technology, open source and completely free.
* [OpenLayers](http://openlayers.org/) - Open source AJAX library.
* [openrouteservice-js](https://github.com/GIScience/openrouteservice-js) - The JavaScript API to consume openrouteservice(s) painlessly!
* [OpenSphere](https://github.com/ngageoint/opensphere#opensphere) - A pluggable, single-page, GIS web application that supports both 2D and 3D views.
* [OSM Building](https://osmbuildings.org[openrouteservice-js](https://github.com/GIScience/openrouteservice-js) - The JavaScript API to consume openrouteservice(s) painlessly!) - A JavaScript library for visualizing OpenStreetMap building geometry on 2D and 3D maps.
* [overpass-turbo](https://github.com/tyrasd/overpass-turbo) - A web based data mining tool for OpenStreetMap using Overpass API.
* [PGRestAPI](https://github.com/spatialdev/PGRestAPI) - Node.js REST API for PostGres Spatial Entities.
* [pixelmatch](https://github.com/mapbox/pixelmatch) - The smallest, simplest and fastest JavaScript pixel-level image comparison library.
* [pouchdb-geospatial](https://github.com/dpmcmlxxvi/pouchdb-geospatial) - The PouchDB Geospatial plugin provides spatial querying of GeoJSON objects right in the browser.
* [procedural-gl-js](https://github.com/felixpalmer/procedural-gl-js) - Procedural GL JS is a library for creating 3D map experiences on the web, written in JavaScript and WebGL. It is built on top THREE.js.
* [proj4js](https://github.com/proj4js/proj4js) - JavaScript library to transform coordinates from one coordinate system to another, including datum transformations.
* [react-leaflet](https://github.com/PaulLeCam/react-leaflet) - React components for Leaflet maps.
* [react-map-gl](https://github.com/uber/react-map-gl) - React friendly API wrapper around MapboxGL JS.
* [reproject](https://github.com/perliedman/reproject) - Change, convert, transform, reproject GeoJSON between different projections/CRS.
* [Spatial](https://github.com/troufster/spatial) - A 2d spatial hash module for node.js.
* [spl.js](https://github.com/jvail/spl.js) - SpatiaLite and friends - sqlite, geos, proj, rttopo - for node (sync API) and browser (async API).
* [SQLite3](https://github.com/mapbox/node-sqlite3) - Asynchronous, non-blocking SQLite3 bindings for Node.js.
* [Supercluster](https://github.com/mapbox/supercluster) - A crazy fast geospatial point clustering library for browsers and Node.
* [SuperMap iClient for JavaScript](http://iclient.supermap.io) - Cloud GIS web client development platform supportted by SuperMap.
* [Terra Draw](https://github.com/JamesLMilner/terra-draw) - A cross provider JavaScript library for drawing on maps
* [TerriaJS](https://github.com/TerriaJS/terriajs) - A library for building rich, web-based geospatial data explorers.
* [Thermo.js](https://github.com/dazuma/thermo.js) - Another heatmap implementation for Javascript.
* [tilegarden](https://github.com/azavea/tilegarden) - Serverless raster and vector map tile generation using Mapnik and AWS Lambda.
* [tilelive-postgis](https://github.com/stepankuzmin/tilelive-postgis) - Implements the tilelive API for generating mapnik vector tiles from PostGIS.
* [TileMantle](https://github.com/naturalatlas/tilemantle) - A tool to warm up your tile server cache. Give it a URL template, geometry, and list of zoom levels and it will request tiles incrementally to warm it up.
* [tilestrata-mapnik](https://github.com/naturalatlas/tilestrata-mapnik) - TileStrata provider for rendering tiles with mapnik.
* [TileStrata](https://github.com/naturalatlas/tilestrata) - A pluggable Node.js map tile server.
* [Turf.js](http://turfjs.org/) - Advanced geospatial analysis for browsers and node.
* [ui-leaflet](https://github.com/angular-ui/ui-leaflet) - AngularJS directive to embed an interact with maps managed by Leaflet library.
* [Vue2Leaflet](https://github.com/KoRiGaN/Vue2Leaflet) - Vue 2 components for Leaflet maps.
* [WebGISService](https://github.com/VicentGN/WebGISService) - Geospatial operations running as a service. Based on NodeJS/ExpressJS and TurfJS. Works with GeoJSON Features and FeaturesCollection.
* [Windshaft](https://github.com/CartoDB/Windshaft) - A Node.js map tile library for PostGIS and torque.js, with CartoCSS styling.

## Julia

* [ArchGDAL](https://github.com/yeesian/ArchGDAL.jl) - Vector and Raster interfaces.
* [ClimateTools.jl](https://github.com/Balinus/ClimateTools.jl) - Collection of commonly-used tools in Climate Science.
* [CoordinateTransformations.jl](https://github.com/JuliaGeometry/CoordinateTransformations.jl) - Julia package to manage simple or complex networks of coordinate system transformations.
* [DataFrames.jl](https://github.com/JuliaStats/DataFrames.jl) - Tools for working with tabular data in Julia.
* [DynamicGrids.jl](https://github.com/cesaraustralia/DynamicGrids.jl) - Generalised framework for building high-performance grid-based spatial simulations, including cellular automata, but also allowing a wider range of behaviours like random jumps and interactions between multiple grids. It is extended by Dispersal.jl for modelling organism dispersal processes.
* [EarthEngine.jl](https://github.com/KMarkert/EarthEngine.jl) - Google Earth Engine in Julia.
* [EcologicalNetwork.jl](https://github.com/PoisotLab/EcologicalNetwork.jl) - This julia package provides a common interface to analyze all types of data on ecological networks.
* [EarthDataLab.jl](https://github.com/JuliaDataCubes/EarthDataLab.jl) - Interface for Reading from the Earth System Datacube.
* [GDALfuns.jl](https://github.com/meggart/GDALfuns.jl) - Auto-generated low-level wrapper for the GDAL library.
* [GeoArrays.jl](https://github.com/evetion/GeoArrays.jl) - Simple geographical raster interaction built on top of ArchGDAL, GDAL and CoordinateTransformations.
* [GeoData.jl](https://github.com/rafaqz/Rasters.jl) - Standardising geospatial raster data in the Julia language.
* [GeoDataFrames.jl](https://github.com/evetion/GeoDataFrames.jl) - Simple geographical vector interaction built on top of ArchGDAL.
* [Geodesy.jl](https://github.com/JuliaGeo/Geodesy.jl) - Work with points defined in various coordinate systems.
* [GeoInterface.jl](https://github.com/JuliaGeo/GeoInterface.jl) - A Julia Protocol for Geospatial Data.
* [GeoJSON.jl](https://github.com/JuliaGeo/GeoJSON.jl) - This library is developed independently of, but is heavily influenced in design by the python-geojson package.
* [GeoMakie.jl](https://github.com/JuliaPlots/GeoMakie.jl) - Geographical plotting utilities for Makie.jl
* [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) - An extensible framework for high-performance geostatistics in Julia.
* [GMT.jl](https://github.com/GenericMappingTools/GMT.jl) - Generic Mapping Tools Library Wrapper for Julia.
* [ImageFeatures.jl](https://github.com/JuliaImages/ImageFeatures.jl) - Image feature detection for the Julia language.
* [ImageFiltering.jl](https://github.com/JuliaImages/ImageFiltering.jl) - ImageFiltering implements blurring, sharpening, gradient computation, and other linear filtering operations, as well nonlinear filters like min/max.
* [ImageMetadata.jl](https://github.com/JuliaImages/ImageMetadata.jl) - ImageMetadata is a simple package providing utilities for working with images that have metadata attached.
* [ImageMorphology.jl](https://github.com/JuliaImages/ImageMorphology.jl) - This package provides morphology-related functionality to the Images.jl project.
* [Images.jl](https://github.com/JuliaImages/Images.jl) - An image processing library for Julia.
* [ImageSegmentation.jl](https://github.com/JuliaImages/ImageSegmentation.jl) - Julia package for multiple Image Segmentation Algorithms.
* [ImageTransformations.jl](https://github.com/JuliaImages/ImageTransformations.jl/tree/master/src) - This package provides support for image resizing, image rotation, and other spatial transformations of arrays.
* [Interpolations.jl](https://github.com/juliohm/Interpolations.jl) - This package implements a variety of interpolation schemes for the Julia language.
* [JuliaGIS](https://github.com/wkearn/GIS.jl) - A package for the visualization and manipulation of geographic data.
* [LASindex.jl](https://github.com/evetion/LASindex.jl) - Pure Julia reader of lasindex .lax files.
* [LasIO.jl](https://github.com/visr/LasIO.jl) - Native Julia package for working with .las pointcloud data.
* [LazIO.jl](https://github.com/evetion/LazIO.jl) - Extends LasIO with Laszip integration.
* [LibGEOS.jl](https://github.com/JuliaGeometry/LibGEOS.jl) - LibGEOS is a LGPL-licensed package for manipulation and analysis of planar geometric objects, based on the libraries GEOS (the engine of PostGIS) and JTS (from which GEOS is ported).
* [LibLAS.jl](https://github.com/visr/LibLAS.jl) - Julia wrapper for LibLAS, a library for reading and writing the LAS LiDAR format.
* [LibSpatialIndex.jl](https://github.com/JuliaGeo/LibSpatialIndex.jl) - A library for spatially indexing kD bounding box data (based on libspatialindex).
* [NearestNeighbors.jl](https://github.com/KristofferC/NearestNeighbors.jl) - High performance nearest neighbor data structures and algorithms for Julia.
* [NetCDF.jl](https://github.com/JuliaGeo/NetCDF.jl) - NetCDF support for the julia programming language.
* [NMEA.jl](https://github.com/zznop/NMEA.jl) - NMEA.jl is a package for parsing NMEA GPS protocol sentences.
* [OpenStreetMaps.jl](https://github.com/tedsteiner/OpenStreetMap.jl) - This package provides basic functionality for parsing, viewing, and working with OpenStreetMap map data.
* [OpenStreetMapX.jl](https://github.com/pszufe/OpenStreetMapX.jl) - Provides basic functionality for parsing, viewing, and working with OpenStreetMap map data.
* [OpenStreetMapXPlot.jl](https://github.com/pszufe/OpenStreetMapXPlot.jl) - Plotting functionality for the OpenStreetMapX.jl (Supports PyPlot.jl and Plots.jl with GR backend).
* [Proj4.jl](https://github.com/JuliaGeo/Proj4.jl) - A simple wrapper around the Proj.4 cartographic projections library.
* [RasterDataSources.jl](https://github.com/EcoJulia/RasterDataSources.jl) - Downloads raster data for local use or for integration into other spatial data packages, like GeoData.jl.
* [RasterIO.jl](https://github.com/wkearn/RasterIO.jl) - Simple Raster Formats for Julia.
* [RegionTrees.jl](https://github.com/rdeits/RegionTrees.jl) - Quadtrees, Octrees, and more in Julia.
* [Shapefile.jl](https://github.com/JuliaGeo/Shapefile.jl) - Parsing .shp files in Julia.
* [SpatialIndexing.jl](https://github.com/alyst/SpatialIndexing.jl) - Spatial data indexing in pure Julia (R*-trees etc).
* [SpectralIndices.jl](https://github.com/awesome-spectral-indices/SpectralIndices.jl) - Julia package for working with spectral indices commonly used in remote sensing and earth observation applications.
* [STAC.jl](https://github.com/JuliaClimate/STAC.jl) - SpatioTemporal Asset Catalog (STAC) julia client.
* [Tinker.jl](https://github.com/JuliaImages/Tinker.jl) - Interactive graphical tool for complex image analysis.
* [Turf.jl](https://github.com/yeesian/Turf.jl) - This library is a port of Turf.js to the Julia programming language for geospatial analysis.
* [ViziCities](https://github.com/UDST/vizicities#getting-started) - A framework for 3D geospatial visualization in the browser.
* [VoronoiDelaunay.jl](https://github.com/JuliaGeometry/VoronoiDelaunay.jl) - Fast, robust construction of 2D Delaunay and Voronoi tessellations on generic point types.
* [Watershed.jl](https://github.com/seung-lab/Watershed.jl) - This is a translation of Zlateski's C++ Watershed code.

## Kotlin

* [geospatial-messenger](https://github.com/sdeleuze/geospatial-messenger) - Geospatial messenger application written with Spring Boot + Kotlin + PostgreSQL.
* [Lets-Plot](https://github.com/JetBrains/lets-plot-kotlin/blob/master/docs/geotools.md) - An open-source plotting library. Together with GeoTools it allows you to visualize geospatial data in Jupyter notebooks or a JVM application.

## Lisp
* [cl-ewkb](https://github.com/filonenko-mikhail/cl-ewkb/) - Common Lisp PostGIS EWKB data model and encoder/decoder.
* [cl-proj](https://github.com/vityok/cl-proj) - CL-PROJ provides CFFI-based Common Lisp bindings for the PROJ.4 library.
* [utm](https://github.com/jl2/utm) - Lisp library for converting between latitude/longitude and UTM.

## Lua

* [geo.lua](https://github.com/RedisLabs/geo.lua) - A helper library for Redis geospatial indices.
* [Tarantool/GIS](https://github.com/tarantool/gis) - A full-featured geospatial extension for Tarantool.
* [TerraME](http://www.terrame.org/doku.php) - TerraME is a programming environment for spatial dynamical modelling. It supports cellular automata, agent-based models, and network models running in 2D cell spaces.

## MATLAB

* [CCDC](https://github.com/GERSL/CCDC) - Algorithm developed for Continuous Change Detection and Classification (CCDC) of land cover using all available Landsat data.
* [ChangeDetectionToolbox](https://github.com/Bobholamovic/ChangeDetectionToolbox) - MATLAB Toolbox for Remote Sensing Change Detection.
* [Cmask](https://github.com/GERSL/Cmask) - This tool called Cmask (Cirrus cloud mask) is used for cirrus cloud detection in Landsat 8 imagery using a time series of data from the Cirrus Band (1.36 – 1.39 µm).
* [COLD](https://github.com/GERSL/COLD) - Algorithm for COntinuous monitoring of Land Disturbance (COLD) using Landsat time series.
* [MFmask](https://github.com/qsly09/MFmask) - Automated cloud and cloud shadow detection for Landsats 4-8 images.

## Nim
* [fp_denoise](https://github.com/jblindsay/fp_denoise) - A tool for de-noising raster digital elevation models.
* [kdtree](https://github.com/jblindsay/kdtree) - A pure Nim k-d tree implementation for efficient spatial querying of point data.
* [wbt_nim](https://github.com/jblindsay/wbt_nim) - A Nim-based API for using the WhiteboxTools geospatial data analysis library.

## Perl
* [address formatting](https://github.com/OpenCageData/address-formatting) - Templates to format geographic addresses.
* [Geo::GDAL](https://metacpan.org/pod/Geo::GDAL) - Perl extension for the GDAL library for geospatial data.

## Python

* [aiocogeo](https://github.com/geospatial-jeff/aiocogeo) - Asynchronous cogeotiff reader.
* [aiocogeo](https://github.com/geospatial-jeff/aiocogeo) - Read Cloud Optimized GeoTiffs without GDAL.
* [Alpha Shape Toolbox](https://github.com/bellockk/alphashape) - Toolbox for constructing alpha shapes.
* [AnaFlow](https://github.com/GeoStat-Framework/AnaFlow) - A python-package containing analytical solutions for the groundwater flow equation.
* [ArcGIS Python API](https://developers.arcgis.com/python/) - ArcGIS API for Python is a Python library for working with maps and geospatial data, powered by web GIS.
* [autoRIFT](https://github.com/leiyangleon/autoRIFT) - Python module of a fast and intelligent algorithm for finding the pixel displacement between two images.
* [Cartopy](http://scitools.org.uk/cartopy/) - A library providing cartographic tools for python for plotting spatial data.
* [cdsapi](https://github.com/ecmwf/cdsapi) - Python API to access the Copernicus Climate Data Store (CDS).
* [cedar-datacube](https://github.com/ceholden/cedar-datacube) - Create Earth engine Datacubes of Analytical Readiness.
* [Centroids](https://github.com/lyzidiamond/centroids) - This application reads a valid geojson FeatureCollection and returns a valid geojson FeatureColleciton of centroids.
* [chupaESRI](https://github.com/johnjreiser/chupaESRI) - ChupaESRI is a Python module/command line tool to extract features from ArcGIS Server map services.
* [Climata](https://github.com/heigeo/climata) - Python library for loading and iterating over climate and flow time series data (from ACIS/NOAA RCCs, CoCoRaHS, Hydromet/USBR, CNRFC ESP/NWS, SNOTEL/AWDB/NRCS, and NWIS/USGS).
* [CoastSat](https://github.com/kvos/CoastSat) - CoastSat is an open-source software toolkit written in Python that enables users to obtain time-series of shoreline position at any coastline worldwide from 30+ years (and growing) of publicly available satellite imagery.
* [cog_validator](https://github.com/rouault/cog_validator) - This is a standalone (Python / Flask) service that allows users to submit GeoTIFF files (preferably by URL) and check their compliance with the Cloud Optimized GeoTIFF (COG) specification.
* [cubo](https://github.com/davemlz/cubo) - Easily create EO mini cubes from STAC in Python.
* [CuPy](https://github.com/cupy/cupy) - NumPy-like API accelerated with CUDA.
* [cuSpatial](https://github.com/rapidsai/cuspatial) - GPU-Accelerated Spatial and Trajectory Data Management and Analytics Library.
* [dask-geopandas](https://github.com/geopandas/dask-geopandas) - Parallelized GeoPandas with Dask.
* [dask-rasterio](https://github.com/dymaxionlabs/dask-rasterio) - Read and write rasters in parallel using Rasterio and Dask.
* [Descartes](https://pypi.python.org/pypi/descartes) - Plot geometries in matplotlib.
* [Detectree](https://github.com/martibosch/detectree) - DetecTree is a Pythonic library to classify tree/non-tree pixels from aerial imagery.
* [EarthPy](https://github.com/earthlab/earthpy) - A package built to support working with spatial data using open source python.
* [elevation](https://github.com/bopen/elevation) - Python script to download global terrain digital elevation models, SRTM 30m DEM and SRTM 90m DEM.
* [eo-box](https://github.com/benmack/eo-box) - Earth observation processing framework for machine learning in Python.
* [EODAG](https://eodag.readthedocs.io/en/latest/) - Command line tool and a plugin-oriented Python framework for searching, aggregating results and downloading remote sensed images while offering a unified API for data access regardless of the data provider.
* [EOmaps](https://github.com/raphaelquast/EOmaps) - Create interactive maps to visualize, analyze and compare geographical datasets (based on matplotlib/cartopy).
* [EOReader](https://github.com/sertit/eoreader) - EOReader is a multi-satellite reader allowing you to open optical and SAR data.
* [fastkml](https://github.com/cleder/fastkml) - Fastkml is a library to read, write and manipulate KML files. It aims to keep it simple and fast (using lxml if available).
* [Fiona](https://fiona.readthedocs.io/en/latest/) - For making it easy to read/write geospatial data formats.
* [forestatrisk](https://github.com/ghislainv/forestatrisk) - Python package to model and forecast the risk of deforestation.
* [FreeType](https://code.google.com/archive/p/freetype-py/) - For converting font glyphs to polygons.
* [geemap](https://github.com/giswqs/geemap) - A Python package for interactive mapping with Google Earth Engine, ipyleaflet, and ipywidgets.
* [geeup](https://github.com/samapriya/geeup) - Simple CLI for Earth Engine Uploads.
* [GemGIS](https://github.com/cgre-aachen/gemgis) - Python-based, open-source geographic information processing library.
* [GeoAI](https://github.com/opengeos/geoai) - GeoAI: Artificial Intelligence for Geospatial Data
* [geoalchemy](https://github.com/geoalchemy/geoalchemy) - Using SQLAlchemy with spatial databases.
* [geoapify](https://github.com/huels-originals/geoapify) - CLI and Python client for Geoapify's location services.
* [geocube](https://github.com/corteva/geocube) - Tool to convert geopandas vector data into rasterized xarray data.
* [GeoDaSpace](https://github.com/GeoDaCenter/GeoDaSpace) - Software for Advanced Spatial Econometrics.
* [GeoPandas](https://github.com/geopandas/geopandas) - Python tools for geographic data.
* [geofileops](https://github.com/geofileops/geofileops) - Python toolbox to process large vector files faster.
* [geojson-shave](https://github.com/ben-nour/geojson-shave) - A Python command-line tool to reduce the size of GeoJSON files.
* [geospatial](https://github.com/giswqs/geospatial) - A collection of Python packages for geospatial analysis and data visualization.
* [GSTools](https://github.com/GeoStat-Framework/GSTools) - A geostatistical toolbox: random fields, variogram estimation, covariance models, kriging and much more.
* [trackintel](https://github.com/mie-lab/trackintel) - A GeoPandas extension for tracking data
* [networkx](http://networkx.github.io/) - To work with networks.
* [Shapely](https://pypi.python.org/pypi/Shapely) - Manipulation and analysis of geometric objects in the Cartesian plane.
* [PyKrige](https://github.com/GeoStat-Framework/PyKrige) - Kriging Toolkit for Python.
* [PySAL](https://pysal.org/pysal/api.html) - For all your spatial econometrics needs.
* [Rasterstats](https://github.com/perrygeo/python-rasterstats/) - Python module for summarizing geospatial raster datasets based on vector geometries.
* [GeoDjango](https://docs.djangoproject.com/en/2.2/ref/contrib/gis/) - Django geographic web framework.
* [geojson-area](https://github.com/scisco/area) - Calculate the area inside of any GeoJSON geometry.
* [geojson-area](https://github.com/scisco/area) - Calculate the area inside of any GeoJSON geometry. This is a port of Mapbox's geojson-area for Python.
* [geojsonio.py](https://github.com/jwass/geojsonio.py) - Open GeoJSON data on geojson.io from Python. geojsonio.py also contains a command line utility that is a Python port of geojsonio-cli.
* [GeoLambda](https://github.com/developmentseed/geolambda) - Create and deploy Geospatial AWS Lambda functions Python.
* [geopatra](https://github.com/Sangarshanan/geopatra) - Interactive Maps with Geopandas.
* [geopy](https://github.com/geopy/geopy) - geopy is a Python 2 and 3 client for several popular geocoding web services.
* [geosnap](https://github.com/spatialucr/geosnap) - geosnap makes it easier to explore, model, analyze, and visualize the social and spatial dynamics of neighborhoods.
* [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy) - GSLIB reimplimented in Python
* [geotiff](https://github.com/Open-Source-Agriculture/geotiff) - A noGDAL tool for reading geotiff files.
* [get_modis](https://github.com/jgomezdans/get_modis) - Downloading MODIS data from the USGS repository.
* [GIPPY](https://github.com/gipit/gippy) - Geospatial Image Processing for Python.
* [gpdvega](https://github.com/iliatimofeev/gpdvega) - gpdvega is a bridge between GeoPandas and Altair that allows to seamlessly chart geospatial data.
* [HyperCoast](https://github.com/opengeos/HyperCoast) - A Python package for visualizing and analyzing hyperspectral data in coastal regions.
* [HyRiver](https://hyriver.readthedocs.io) - A suite of Python packages for retrieving various geospatial/temporal data from public web services.
* [HPGL](https://github.com/hpgl/hpgl) - High Perfomance Geostatistics Library.
* [Intake-stac](https://github.com/intake/intake-stac) - This is an intake data source for SpatioTemporal Asset Catalogs (STAC).
* [LANDSAT-Download](https://github.com/olivierhagolle/LANDSAT-Download) - Automated download of LANDSAT data from USGS website.
* [landsat-extract-gee](https://github.com/loicdtx/landsat-extract-gee) - Get Landsat surface reflectance time-series from google earth engine.
* [Landsat-util](https://github.com/developmentseed/landsat-util) - Landsat-util is a command line utility that makes it easy to search, download, and process Landsat imagery.
* [landsatxplore](https://github.com/yannforget/landsatxplore) - Search and download Landsat scenes from EarthExplorer.
* [LARD](https://github.com/deel-ai/LARD) - A runway dataset and a generator of synthetic aerial images with automatic labeling.
* [leafmap](https://github.com/giswqs/leafmap) - A Python package for geospatial analysis and interactive mapping with minimal coding in a Jupyter environment.
* [Lets-Plot](https://lets-plot.org) - An open-source plotting library supporting visualization of geospatial data on static or interactive maps.
* [lidar](https://github.com/giswqs/lidar) - Terrain and hydrological analysis using digital elevation models (DEMs).
* [localtileserver](https://github.com/banesullivan/localtileserver) - A Python package for serving tiles from large raster files in the Slippy Maps standard (i.e., `/zoom/x/y.png`) for visualization in Jupyter with `ipyleaflet` or `folium`.
* [LT-ChangeDB](https://github.com/eMapR/LT-ChangeDB) - Scripts to extract spectral change information from LandTrendr data to a geodatabase.
* [Mahotas-imread](https://github.com/luispedro/imread) - Read images to numpy arrays.
* [Mahotas](https://github.com/luispedro/mahotas) - Mahotas is a library of fast computer vision algorithms (all implemented in C++ for speed) operating over numpy arrays.
* [mapboxgl-jupyter](https://github.com/mapbox/mapboxgl-jupyter) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook.
* [Mapchete](https://github.com/ungarj/mapchete) - Mapchete processes raster and vector geodata in digestable chunks. Tile-based geodata processing.
* [mapclassify](https://github.com/pysal/mapclassify) - Classification schemes for choropleth mapping.
* [momepy](https://github.com/martinfleis/momepy) - Momepy is a library for quantitative analysis of urban form - urban morphometrics.
* [MovingPandas](https://github.com/anitagraser/movingpandas) - Implementation of Trajectory classes and functions built on top of GeoPandas.
* [ MuseoToolBox](https://github.com/nkarasiak/MuseoToolBox) - Museo ToolBox is a python library to simplify the use of raster/vector, especially for machine learning and remote sensing.
* [networkit](https://github.com/networkit/networkit) - NetworKit is a growing open-source toolkit for large-scale network analysis.
* [networkx](http://networkx.github.io/) - To work with networks.
* [NodeBox-opengl](http://www.cityinabottle.org/nodebox/) - For playing around with animations.
* [Ogcserver](https://github.com/mapnik/OGCServer) - Python WMS implementation using Mapnik.
* [Open-Elevation](https://github.com/Jorl17/open-elevation) - A free and open-source alternative to Google Elevation API.
* [openrouteservice-py](https://github.com/GIScience/openrouteservice-py) - The Python API to consume openrouteservice(s) painlessly!
* [Open Topo Data](https://github.com/ajnisbet/opentopodata) - Open Topo Data is a REST API server for your elevation data.
* [orbit-predictor](https://github.com/satellogic/orbit-predictor) - Orbit Predictor is a Python library to propagate orbits of Earth-orbiting objects (satellites, ISS, Santa Claus, etc) using TLE (Two-Line Elements set).
* [osm2geojson](https://github.com/aspectumapp/osm2geojson) - Parse OpenStreetMap (OSM) XML and Overpass JSON/XML.
* [OSMnet](https://github.com/UDST/osmnet) - Tools for the extraction of OpenStreetMap street network data.
* [QuackOSM](https://github.com/kraina-ai/quackosm) - Library and a CLI tool for downloading, filtering and transforming `*.osm.pbf` files into `GeoParquet` files using DuckDB.
* [pandana](https://github.com/UDST/pandana) - Pandas Network Analysis - dataframes of network queries, quickly.
* [Peartree](https://github.com/kuanb/peartree) - Peartree: A library for converting transit data into a directed graph for network analysis.
* [pipgeo](https://github.com/samapriya/pipgeo) - pipgeo: CLI for Unofficial windows Geospatial library wheels.
* [Planet Movement](https://github.com/rhammell/planet-movement) - Python module enables the searching and processing of Planet imagery to highlight object movement between valid image pairs.
* [planetary-computer](https://pypi.org/project/planetary-computer/) - Python library for interacting with the Microsoft Planetary Computer.
* [PODPAC](https://podpac.org/) - PODPAC is a python library that builds on the scientific python ecosystem to enable simple, reproducible geospatial analyses that run locally or in the cloud.
* [prosail](https://github.com/jgomezdans/prosail) - Python bindings for the PROSAIL canopy reflectance model.
* [pyCSW](http://pycsw.org/) - Fully implements the OpenGIS Catalogue Service Implementation Specification (Catalogue Service for the Web). Initial development started in 2010 (more formally announced in 2011). The project is certified OGC Compliant, and is an OGC Reference Implementation.
* [pydeck](https://pydeck.gl) – Python bindings for deck.gl
* [pydelatin](https://github.com/kylebarron/pydelatin) - Python bindings to `hmm` for fast terrain mesh generation
* [pyDEM](https://github.com/creare-com/pydem) - Python library for Global Hydrology Analysis. Used to calculate upstream contributing area, aspect, slope, and topographic wetness index.
* [pygeoapi](https://pygeoapi.io/)pygeoapi is a Python server implementation of the OGC API suite of standards. The project emerged as part of the next generation OGC API efforts in 2018 and provides the capability for organizations to deploy a RESTful OGC API endpoint using OpenAPI, GeoJSON, and HTML.
* [pygeoif](https://github.com/cleder/pygeoif) - PyGeoIf provides a GeoJSON-like protocol for geo-spatial (GIS) vector data. A simple, pure Python implementation of geometric objects and operations, useful for basic GIS tasks.
* [pyGEOS](https://github.com/pygeos/pygeos) - Exposes geospatial operations from GEOS into Python.
* [pyGMT](https://github.com/GenericMappingTools/pygmt) - Pythonic interface for the Generic Mapping Tools (GMT).
* [pyimpute](https://github.com/perrygeo/pyimpute) - Python module for geospatial prediction using scikit-learn and rasterio.
* [pyinterpolate](https://github.com/DataverseLabs/pyinterpolate) - Ordinary Kriging, Simple Kriging, Indicator Kriging, Poisson Kriging, Area-to-Point Kriging, Semivariogram Deconvolution, and variogram modeling in Python
* [pyKriging](https://github.com/capaulson/pyKriging) - N-dimensional kriging.
* [pyle38](https://github.com/iwpnd/pyle38) - Asynchronous Client for the worlds fastest in-memory geo-database Tile38
* [pymap3d](https://github.com/scivision/pymap3d) - Python 3D coordinate conversions for geospace ecef enu eci.
* [pymartini](https://github.com/kylebarron/pymartini) - A Cython port of Martini for fast RTIN terrain mesh generation
* [Pyncf](https://github.com/karimbahgat/pyncf) - Pure Python NetCDF file reading and writing.
* [PyPostal](https://github.com/openvenues/pypostal) - Python bindings to libpostal for fast international address parsing/normalization.
* [PyProj](https://github.com/jswhit/pyproj) - For conversions between projections.
* [PyQGIS](http://docs.qgis.org/testing/en/docs/pyqgis_developer_cookbook/) - Python for QGIS.
* [pyroSAR](https://github.com/johntruckenbrodt/pyroSAR) - A Python Framework for Large-Scale SAR Satellite Data Processing.
* [pyrosm](https://github.com/HTenkanen/pyrosm) - Read OpenStreetMap data from Protobuf files into GeoDataFrame with Python, faster.
* [PyShp](https://code.google.com/archive/p/pyshp/) - For reading and writing shapefiles.
* [PySTAC](https://github.com/stac-utils/pystac) - Python library for working with any SpatioTemporal Asset Catalog (STAC).
* [Python Geocoder](https://github.com/DenisCarriere/geocoder) - Simple and consistent geocoding library written in Python.
* [python-opencage-geocoder](https://github.com/OpenCageData/python-opencage-geocoder) - A Python module that uses the OpenCage Geocoding API.
* [pyWPS](http://pywps.org/) - An implementation of the Web Processing Service standard from the Open Geospatial Consortium. PyWPS is written in Python. It enables integration, publishing and execution of Python processes via the WPS standard.
* [RasterFrames](https://github.com/locationtech/rasterframes) - RasterFrames brings together Earth-observation (EO) data access, cloud computing, and DataFrame-based data science.
* [Rasterio](https://github.com/mapbox/rasterio) - Rasterio employs GDAL under the hood for file I/O and raster formatting.
* [Rasterstats](https://github.com/perrygeo/python-rasterstats/) - Python module for summarizing geospatial raster datasets based on vector geometries.
* [RichDEM](https://github.com/r-barnes/richdem) - High-performance Terrain and Hydrology Analysis.
* [rio-cogeo](https://github.com/mapbox/rio-cogeo) - CloudOptimized GeoTIFF creation plugin for rasterio.
* [rio-color](https://github.com/mapbox/rio-color) - Color correction plugin for rasterio.
* [rio-hist](https://github.com/mapbox/rio-hist) - Histogram matching plugin for rasterio.
* [rio-tiler](https://github.com/mapbox/rio-tiler) - Get mercator tile from landsat, sentinel or other AWS hosted raster.
* [RIOS](https://www.rioshome.org/en/latest/) - Raster I/O Simplification. A set of python modules which makes it easy to write raster processing code in Python.
* [rioxarray](https://github.com/corteva/rioxarray) - rasterio xarray extension.
* [routing-py](https://github.com/gis-ops/routing-py) - Python library to access all public routing, isochrones and matrix APIs in a consistent manner.
* [RSGISLib](http://www.rsgislib.org/) - The Remote Sensing and GIS software library (RSGISLib) is a collection of tools for processing remote sensing and GIS datasets. The tools are accessed using Python bindings or an XML interface.
* [Rtree](http://toblerity.org/rtree/) - For efficiently querying spatial data.
* [S2P - Satellite Stereo Pipeline](https://github.com/cmla/s2p) - S2P is a Python library and command line tool that implements a stereo pipeline which produces elevation models from images taken by high resolution satellites.
* [satpy](https://satpy.readthedocs.io/en/latest/) - Satpy is a python library for reading, manipulating, and writing data from remote-sensing earth-observing meteorological satellite instruments.
* [scikit-eo](https://github.com/ytarazona/scikit-eo) - A Python package for Remote Sensing Tools.
* [SciKit-Gstat](https://scikit-gstat.readthedocs.io/en/latest/) - SciKit-Gstat is a scipy-styled analysis module for variogram analysis.
* [Scikit-image](http://scikit-image.org/) - Scikit-image is a collection of algorithms for image processing.
* [scikit-mobility](https://github.com/scikit-mobility/scikit-mobility) - Mobility analysis in Python.
* [sentinelsat](https://github.com/sentinelsat/sentinelsat) - Search and download Copernicus Sentinel satellite images.
* [Shapely](https://pypi.python.org/pypi/Shapely) - Manipulation and analysis of geometric objects in the Cartesian plane.
* [Siphon](https://github.com/unidata/siphon) - A collection of Python utilities for retrieving atmospheric and oceanic data from remote sources, focusing on being able to retrieve data from Unidata data technologies, such as the THREDDS data server.
* [som-tsp](https://github.com/DiegoVicen/som-tsp) - Solving the Traveling Salesman Problem using Self-Organizing Maps.
* [Spectral Python](https://github.com/spectralpython/spectral) - Python module for hyperspectral image processing.
* [spyndex](https://github.com/awesome-spectral-indices/spyndex) - Awesome Spectral Indices in Python.
* [srai](https://github.com/kraina-ai/srai) - Spatial Representations for Artificial Intelligence. Set of tools for geospatial machine learning, data acquisition and wrangling.
* [stac-fastapi](https://github.com/stac-utils/stac-fastapi) - STAC API implementation with FastAPI.
* [stackstac](https://github.com/gjoseph92/stackstac) - Turn a STAC catalog into a dask-based xarray.
* [stactools](https://github.com/stac-utils/stactools) - Command line utility and Python library for STAC.
* [starfm4py](https://github.com/nmileva/starfm4py) - The STARFM fusion model for Python (image fusion).
* [Statsmodels](http://statsmodels.sourceforge.net/) - Python module that allows users to explore data, estimate statistical models, and perform statistical tests.
* [telluric](https://github.com/satellogic/telluric) - telluric is a Python library to manage vector and raster geospatial data in an interactive and easy way.
* [thunder](https://github.com/thunder-project/thunder) - Thunder is an ecosystem of tools for the analysis of image and time series data in Python.
* [Tobler](https://github.com/pysal/tobler) - Tobler is a python package for areal interpolation, dasymetric mapping, and change of support.
* [ts-raster](https://github.com/adbeda/ts-raster) - ts-raster is a python package for analyzing time-series characteristics from raster data. It allows feature extraction, dimension reduction and applications of machine learning techniques for geospatial data.
* [Turfpy](https://github.com/omanges/turfpy) - This is Python library for performing geo spatial data analysis. This is an python alternative for turf.js.
* [unmixing](https://github.com/arthur-e/unmixing) - Interactive tools and functions for performing linear spectral mixture analysis (LSMA) and spatially adaptive spectral mixture analysis (SASMA).
* [untiler](https://github.com/mapbox/untiler) - Stitch image tiles into larger composite TIFs.
* [urbanaccess](https://github.com/UDST/urbanaccess) - A tool for computing GTFS transit and OSM pedestrian networks for accessibility analysis.
* [Urban Mapper](https://github.com/VIDA-NYU/UrbanMapper) – 🗺️ Spatial Join & Enrich any `urban layer` (Roads, Intersections, Sidewalks, Crosswalks, Neighborhoods, Cities, States, Countries) given any `external urban dataset` of interest, and streamline your urban analysis with Scikit-Learn-Like pipelines!
* [urbansim](https://github.com/UDST/urbansim) - New version of UrbanSim, a platform for modeling metropolitan real estate markets.
* [urban-worm](https://github.com/billbillbilly/urbanworm) - a Python library that integrates remote sensing imagery, street view data, and multi-modal models for spatial reasoning, focusing on built environments and urban units
* [USGS API](https://github.com/kapadia/usgs) - USGS is a python module for interfacing with the US Geological Survey's API.
* [Verde](https://github.com/fatiando/verde) - Verde is a Python library for processing spatial data (bathymetry, geophysics surveys, etc) and interpolating it on regular grids (i.e., gridding).
* [whitebox](https://github.com/giswqs/whitebox) - Python frontend for [WhiteboxTools](https://github.com/jblindsay/whitebox-tools).
* [WhiteboxTools-ArcGIS](https://github.com/giswqs/WhiteboxTools-ArcGIS) - ArcGIS Python Toolbox for [WhiteboxTools](https://github.com/jblindsay/whitebox-tools).
* [xarray-spatial](https://github.com/makepath/xarray-spatial) - xarray-spatial implements common raster analysis functions using Numba and provides an easy-to-install, easy-to-extend codebase for raster analysis.
* [xarray](http://xarray.pydata.org/en/stable/) - xarray (formerly xray) is an open source project and Python package that aims to bring the labeled data power of pandas to the physical sciences, by providing N-dimensional variants of the core pandas data structures.
* [xarray_leaflet](https://github.com/davidbrochart/xarray_leaflet) - An xarray extension for tiled map plotting.
* [xcube](https://github.com/dcs4cop/xcube) - xcube is a Python package for generating and exploiting data cubes powered by xarray, dask, and zarr.
* [xyzservices](https://github.com/geopandas/xyzservices) - A unified source of XYZ tile providers in Python.
* [YATSM](https://github.com/ceholden/yatsm) - Yet Another Timeseries Model (YATSM) is a Python package for utilizing a collection of timeseries algorithms and methods designed to monitor the land surface using remotely sensed imagery.

## PHP

* [FreeGeoDB](https://github.com/delight-im/FreeGeoDB) - Free database of geographic place names and corresponding geospatial data.
* [geojson](https://github.com/jmikola/geojson) - GeoJSON implementation for PHP.
* [GeoPHP](https://geophp.net/) - Advanced geometry operations in PHP.
* [geospatial](https://github.com/php-geospatial/geospatial) - PHP Extension to handle common geospatial functions.
* [laragis](https://github.com/ralphschindler/laragis) - A standalone Geo/GIS Provider for Laravel.
* [laravel-geo](https://github.com/eleven-lab/laravel-geo) - GeoSpatial integration on Laravel 5.2+ that supports MySQL and PostgreSQL.
* [li3_geo](https://github.com/nateabele/li3_geo) - Adds geospatial support to Lithium for multiple databases, including MongoDB, CouchDB and MySQL.
* [PHP Azure Maps Provider](https://github.com/max-langerman/azure-maps-provider) - A PHP Azure Maps Geocoder Provider.
* [PHP7 Mapnik](https://github.com/garrettrayj/php7-mapnik) - PHP extension for geospatial rendering with Mapnik.
* [shapefile](https://github.com/phpmyadmin/shapefile) - ESRI ShapeFile library for PHP.
* [ShapeReader](https://github.com/muka/ShapeReader) - A PHP library to parse ESRI Shape files.


## R

* [ade4](https://cran.r-project.org/web/packages/ade4/index.html) - Tools for multivariate data analysis. Several methods are provided for the analysis (i.e., ordination) of one-table (e.g., principal component analysis, correspondence analysis), two-table (e.g., coinertia analysis, redundancy analysis), three-table (e.g., RLQ analysis) and K-table (e.g., STATIS, multiple coinertia analysis).
* [adehabitat](https://cran.r-project.org/web/packages/adehabitat/index.html) - A collection of tools for the analysis of habitat selection by animals.
* [adehabitatHR](https://cran.r-project.org/web/packages/adehabitatHR/index.html) - A collection of tools for the estimation of animals home range.
* [adehabitatHS](https://cran.r-project.org/web/packages/adehabitatHS/index.html) - A collection of tools for the analysis of habitat selection.
* [adehabitatLT](https://cran.r-project.org/web/packages/adehabitatLT/index.html) - A collection of tools for the analysis of animal movements.
* [adehabitatMA](https://cran.r-project.org/web/packages/adehabitatMA/index.html) - A collection of tools to deal with raster maps.
* [Akima](https://cran.r-project.org/web/packages/akima/index.html) - Interpolation of Irregularly and Regularly Spaced Data.
* [AMOEBA](https://cran.r-project.org/web/packages/AMOEBA/index.html) - A function to calculate spatial clusters using the Getis-Ord local statistic. It searches irregular clusters (ecotopes) on a map.
* [bfastSpatial](https://github.com/loicdtx/bfastSpatial) - Package to pre-process gridded time-series data in order for them to be analyzed with change detection algorithms such as bfast. Uses classes from the raster package and includes utilities to run the algorithms and post-process the results.
* [biodivMapR](https://github.com/jbferet/biodivMapR) - R package for α- and β-diversity mapping using remotely-sensed images.
* [biomod2](https://github.com/biomodhub/biomod2) - Computer platform for ensemble forecasting of species distributions, enabling the treatment of a range of methodological uncertainties in models and the examination of species-environment relationships.
* [bivariatemaps](https://github.com/hidasi/bivariatemaps) - Generates bivariate maps and intersects shapefiles with grids and excludes cells based on area coverage. 
* [CARBayes](https://cran.r-project.org/web/packages/CARBayes/index.html) - Package implements Bayesian hierarchical spatial areal unit models.
* [cartography](https://github.com/riatelab/cartography) - Thematic Cartography with R.
* [censobr](https://github.com/ipeaGIT/censobr) - R package to download data from Brazil's Population Census.
* [classInt](https://cran.r-project.org/web/packages/classInt/index.html) - Selected commonly used methods for choosing univariate class intervals for mapping or other graphics purposes.
* [climateR](https://github.com/mikejohnson51/climateR) - An R package for getting point and gridded climate data by AOI.
* [CompRandFld](https://cran.r-project.org/web/packages/CompRandFld/index.html) - A set of procedures for the analysis of Random Fields using likelihood and non-standard likelihood methods is provided.
* [constrainedKriging](https://cran.r-project.org/web/packages/constrainedKriging/index.html) - Provides functions for efficient computations of nonlinear spatial predictions with local change of support.
* [cshapes](https://cran.r-project.org/web/packages/cshapes/index.html) - Package for CShapes, a GIS dataset of country boundaries (1946-today). Includes functions for data extraction and the computation of distance matrices and -lists.
* [dbmss](https://cran.r-project.org/web/packages/dbmss/index.html) - Simple computation of spatial statistic functions of distance to characterize the spatial structures of mapped objects.
* [deldir](https://cran.r-project.org/web/packages/deldir/index.html) - Calculates the Delaunay triangulation and the Dirichlet or Voronoi tessellation (with respect to the entire plane) of a planar point set.
* [dggridR](https://cran.r-project.org/web/packages/dggridR/index.html) - Provides an interface to DGGRID for working with discrete global grids, using hexagons, triangles, and diamonds to overcome the issue that every bin have the same area.
* [dsmSearch](https://github.com/land-info-lab/dsmSearch) - The package dsmSearch offers functions for retrieving high-resolution Digital Surface Models (DSM) and Light Detection and Ranging (LiDAR) data
* [DSpat](https://cran.r-project.org/web/packages/DSpat/index.html) - Fits inhomogeneous Poisson process spatial models to line transect sampling data and provides estimate of abundance within a region.
* [dtwSat](https://github.com/vwmaus/dtwSat) - Time-Weighted Dynamic Time Warping for satellite image time series analysis.
* [earthEngineGrabR](https://github.com/JesJehle/earthEngineGrabR) - The earthEngineGrabR is an interface between R and the Google Earth Engine, which simplifies the acquisition of remote sensing data.
* [ecespa](https://cran.r-project.org/web/packages/ecespa/index.html) - Functions for Spatial Point Pattern Analysis.
* [edgebundle](https://github.com/schochastics/edgebundle) - R package implementing edge bundling algorithms.
* [elsa](https://github.com/babaknaimi/elsa) - ELSA (entropy-based local indicator of spatial association) is a novel spatial statistic to measure local spatial autocorrelation in both categorical and continuous spatial data.
* [exactextractr](https://github.com/isciences/exactextractr) - R package for fast and accurate raster zonal statistics.
* [ExceedanceTools](https://cran.r-project.org/web/packages/ExceedanceTools/index.html) - Tools for constructing confidence regions for exceedance regions and contour lines.
* [fasterize](https://github.com/ecohealthalliance/fasterize) - High performance raster conversion for modern spatial data.
* [ffraster](https://github.com/hypertidy/ffraster) - Treat ff arrays as raster objects, and vice versa.
* [FieldSim](https://cran.r-project.org/web/packages/FieldSim/index.html) - Tools for random fields and bridges simulations.
* [forestError](https://github.com/benjilu/forestError) - A Unified Framework for Random Forest Prediction Error Estimation.
* [ForesToolboxRS](https://github.com/ytarazona/ForesToolboxRS) - R package providing a variety of tools and algorithms for the processing and analysis of satellite images for the various applications of Remote Sensing for Earth Observations.
* [FRK](https://cran.r-project.org/web/packages/FRK/index.html) - Is a tool for spatial/spatio-temporal modelling and prediction with large datasets.
* [gdalcubes_R](https://github.com/appelmar/gdalcubes_R) - R package for gdalcubes to process collections of Earth observation image collection as on demand data cubes.
* [gdalio](https://github.com/hypertidy/gdalio) - The goal of gdalio is to read data direct with GDAL warp, with an assumed grid specification.
* [gdalraster](https://github.com/USDAForestService/gdalraster) - R Bindings to the GDAL Raster API.
* [geoaxe](https://cran.r-project.org/web/packages/geoaxe/index.html) - Split 'geospatial' objects into pieces. Includes support for some spatial object inputs, 'Well-Known Text', and 'GeoJSON'.
* [geobr](https://github.com/ipeaGIT/geobr) - Package to download official spatial data sets of Brazil.
* [geodist](https://github.com/hypertidy/geodist) - Ultra lightweight, ultra fast calculation of geo distances.
* [geocmeans](https://github.com/JeremyGelb/geocmeans) - An R package to perform Spatial Fuzzy C-means.
* [geojsonio](https://cran.r-project.org/web/packages/geojsonio/index.html) - Convert data to 'GeoJSON' or 'TopoJSON' from various R classes, including vectors, lists, data frames, shape files, and spatial classes.
* [geojsonsf](https://github.com/SymbolixAU/geojsonsf) - Conversion between sf and geojson.
* [geom](https://github.com/paleolimbot/geom) - Vectorized geometries and low-level GEOS access.
* [GEOmap](https://cran.r-project.org/web/packages/GEOmap/index.html) - Topographic and Geologic Mapping.
* [geoR](https://cran.r-project.org/web/packages/geoR/index.html) - Analysis of Geostatistical Data.
* [geoRglm](https://cran.r-project.org/web/packages/geoRglm/index.html) - Functions for inference in generalised linear spatial models.
* [georob](https://cran.r-project.org/web/packages/georob/index.html) - Provides functions for fitting linear models with spatially correlated errors by robust and Gaussian Restricted Maximum Likelihood and for computing robust and customary point and block kriging predictions, along with utility functions for cross-validation and for unbiased back-transformation of kriging predictions of log-transformed data.
* [geos](https://github.com/paleolimbot/geos) - Open Source Geometry Engine ('GEOS') R API.
* [geospacom](https://cran.r-project.org/web/packages/geospacom/index.html) - Generates distance matrices from shape files and represents spatially weighted multilevel analysis results.
* [GeospatialLineGraphs](https://github.com/Brideau/GeospatialLineGraphs) - A library for creating geospatial line graphs along lines of latitude.
* [geosphere](https://cran.r-project.org/web/packages/geosphere/index.html) - Permits computations of distance and area to be carried out on spatial data in geographical coordinates.
* [geospt](https://cran.r-project.org/web/packages/geospt/index.html) - Contains some geostatistical and radial basis functions, including prediction and cross validation.
* [geotargets](https://github.com/njtierney/geotargets) - Targets extensions for geospatial data.
* [geovctrs](https://github.com/paleolimbot/geovctrs) - Common Classes and Data Structures for Geometry Vectors.
* [GeoXp](https://cran.r-project.org/web/packages/GeoXp/index.html) - Permits interactive graphical exploratory spatial data analysis.
* [getSpatialData](https://github.com/16EAGLE/getSpatialData) - An R package making it easy to query, preview, download and preprocess multiple kinds of spatial data via R.
* [ggmap](https://cran.r-project.org/web/packages/ggmap/index.html) - Spatial Visualization with ggplot2.
* [ggsn](https://cran.r-project.org/web/packages/ggsn/index.html) - Adds north symbols and scale bars in kilometers to maps in geographic or metric coordinates.
* [ggspatial](https://github.com/paleolimbot/ggspatial) - A ggplot2 R extension for plotting Spatial* objects.
* [giscoR](https://github.com/rOpenGov/giscoR) - An API package that helps to retrieve data from Eurostat - GISCO (the Geographic Information System of the COmmission).
* [glmmBUGS](https://cran.r-project.org/web/packages/glmmBUGS/index.html) - Automates running Generalized Linear Mixed Models, including spatial models, with WinBUGS, OpenBUGS and JAGS.
* [gmt](https://cran.r-project.org/web/packages/gmt/index.html) - Interface between the GMT map-making software and R.
* [googleway](https://github.com/SymbolixAU/googleway) - R Package for accessing and plotting Google Maps.
* [Grid2Polygons](https://cran.r-project.org/web/packages/Grid2Polygons/index.html) - Converts a spatial object from class SpatialGridDataFrame to SpatialPolygonsDataFrame.
* [GriegSmith](https://cran.r-project.org/web/packages/GriegSmith/index.html) - Uses the Grieg-Smith method on 2 dimensional spatial data.
* [gstat](https://cran.r-project.org/web/packages/gstat/index.html) - Spatio-Temporal Geostatistical Modelling, Prediction and Simulation.
* [gwrr](https://cran.r-project.org/web/packages/gwrr/index.html) - Fits geographically weighted regression (GWR) models and has tools to diagnose and remediate collinearity in the GWR models.
* [gtfs2gps](https://github.com/ipeaGIT/gtfs2gps) - Convert GTFS data into a data.table with GPS-like records in R.
* [hdeco](https://cran.r-project.org/web/packages/hdeco/index.html) -  Provides hierarchical decomposition of entropy for categorical map comparisons.
* [HSAR](https://cran.r-project.org/web/packages/HSAR/index.html) - A library of the Hierarchical Spatial Autoregressive Model (HSAR), based on a Bayesian Markov Chain Monte Carlo (MCMC) algorithm.
* [intamap](https://cran.r-project.org/web/packages/intamap/index.html) - Procedures for automated interpolation.
* [ipdw](https://cran.r-project.org/web/packages/ipdw/index.html) - Functions are provided to interpolate geo-referenced point data via Inverse Path Distance Weighting.
* [kuenm](https://github.com/marlonecobos/kuenm) - kuenm is an R package designed to make the process of model calibration and final model creation easier and more reproducible, and at the same time more robust.
* [landmap](https://github.com/EnvirometriX/landmap) - Provides methodology for automated mapping i.e. spatial interpolation and/or prediction using Ensemble Machine Learning.
* [Landsat](https://cran.r-project.org/web/packages/landsat/index.html) - Radiometric and topographic correction of satellite imagery.
* [LandsatTS](https://github.com/logan-berner/LandsatTS) - An R package to facilitate retrieval, cleaning, cross-calibration, and phenological modeling of Landsat time-series data.
* [landscapemetrics](https://github.com/r-spatialecology/landscapemetrics) - landscapemetrics is an R package for calculating landscape metrics for categorical landscape patterns in a tidy workflow.
* [latticeDensity](https://cran.r-project.org/web/packages/latticeDensity/index.html) -  Contains functions that compute the lattice-based density estimator of Barry and McIntyre.
* [lawn](https://cran.r-project.org/web/packages/lawn/index.html) - Client for 'Turfjs' for 'geospatial' analysis. The package revolves around using 'GeoJSON' data.
* [lctools](https://cran.r-project.org/web/packages/lctools/index.html) - Package provides researchers and educators with easy-to-learn user friendly tools for calculating key spatial statistics and to apply simple as well as advanced methods of spatial analysis in real data.
* [leafletR](https://cran.r-project.org/web/packages/leafletR/index.html) - Interactive Web-Maps Based on the Leaflet JavaScript Library.
* [LPDynR](https://github.com/xavi-rp/LPDynR) - An R-package to calculate Land Productivity Dynamics using variables derived from Earth Observation imagery.
* [libproj](https://github.com/paleolimbot/libproj) - C API for high-performance geometry operations within the R package framework.
* [lidR](https://github.com/Jean-Romain/lidR) - R package for airborne LiDAR data manipulation and visualisation for forestry application.
* [lucCalculus](https://github.com/e-sensing/lucCalculus) - Spatiotemporal calculus for land use change trajectories.
* [magclass](https://cran.r-project.org/web/packages/magclass/index.html) - Data class for increased interoperability working with spatial- temporal data together with corresponding functions and methods (conversions, basic calculations and basic data manipulation).
* [Makurhini](https://github.com/connectscape/Makurhini) - R package for calculating fragmentation and landscape connectivity indices used in conservation planning.
* [mapboxapi](https://github.com/walkerke/mapboxapi) - R interface to Mapbox web services.
* [mapdeck](https://github.com/SymbolixAU/mapdeck) - R interface to Deck.gl and Mapbox.
* [mapproj](https://cran.r-project.org/web/packages/mapproj/index.html) - Map Projections.
* [maps](https://cran.r-project.org/web/packages/maps/index.html) - Draw Geographical Maps.
* [mapscanner](https://github.com/ropensci/mapscanner) - R package to print maps, draw on them, and scan them back in.
* [mapsf](https://github.com/riatelab/mapsf) - Thematic cartography with R.
* [maptools](https://cran.r-project.org/web/packages/maptools/index.html) - Tools for Reading and Handling Spatial Objects.
* [mapview](https://r-spatial.github.io/mapview/index.html) - mapview provides functions to very quickly and conveniently create interactive visualisations of spatial data.
* [marmap](https://cran.r-project.org/web/packages/marmap/index.html) - Package is designed for downloading, plotting and manipulating bathymetric and topographic data in R.
* [marmap](https://github.com/ericpante/marmap) - Import, plot and analyze bathymetric and topographic data.
* [maxnet](https://github.com/mrmaxent/maxnet) - R package for modelling species geographic distributions. It implements much of the functionality of the Maxent Java application.
* [McSpatial](https://cran.r-project.org/web/packages/McSpatial/index.html) - Provides functions for locally weighted regression, semiparametric and conditionally parametric regression, fourier and cubic spline functions, GMM and linearized spatial logit and probit, k-density functions and counterfactuals, nonparametric quantile regression and conditional density functions, Machado-Mata decomposition for quantile regressions, spatial AR model, repeat sales models, and conditionally parametric logit and probit.
* [micromap](https://cran.r-project.org/web/packages/micromap/index.html) - Package provides linked micromaps using ggplot2.
* [ModelMap](https://cran.r-project.org/web/packages/ModelMap/index.html) - Creates sophisticated models of training data and validates the models with an independent test set, cross validation, or in the case of Random Forest Models, with Out Of Bag (OOB) predictions on the training data.
* [ModelR](https://github.com/Model-R/modelr_pkg) - A workflow for ecological niche models based on dismo.
* [moveVis](https://github.com/16EAGLE/moveVis) - An R package providing tools to visualize movement data (e.g. from GPS tracking) and temporal changes of environmental data (e.g. from remote sensing) by creating video animations.
* [MTA](https://github.com/riatelab/MTA) - Multiscalar Territorial Analysis is an R package for multiscalar territorial analysis based on various contexts.
* [ncdf4](https://cran.r-project.org/web/packages/ncdf4/index.html) - Provides a high-level R interface to data files written using Unidata's netCDF library (version 4 or earlier).
* [ncdfgeom](https://github.com/USGS-R/ncdfgeom) - NetCDF-CF Geometry and Timeseries Tools for R.
* [ngspatial](https://cran.r-project.org/web/packages/ngspatial/index.html) - Provides tools for analyzing spatial data, especially non- Gaussian areal data.
* [nlme](https://cran.r-project.org/web/packages/nlme/index.html) - Fit and compare Gaussian linear and nonlinear mixed-effects models.
* [nngeo](https://github.com/michaeldorman/nngeo) - k-Nearest Neighbor Join for Spatial Data.
* [OasisR](https://cran.r-project.org/web/packages/OasisR/index.html) - A set of indexes and tests for the analysis of social segregation.
* [OpenImageR](https://github.com/mlampros/OpenImageR) - Image processing Toolkit in R.
* [openrouteservice-r](https://github.com/GIScience/openrouteservice-r) - R package to query openrouteservice.org.
* [OpenStreetMap](https://cran.r-project.org/web/packages/OpenStreetMap/index.html) - Access to Open Street Map Raster Images.
* [osmar](https://cran.r-project.org/web/packages/osmar/index.html) - Provides infrastructure to access OpenStreetMap data from different sources.
* [osmdata](https://github.com/ropensci/osmdata) - R package for downloading OpenStreetMap data.
* [osmextract](https://github.com/ropensci/osmextract) - Download and import OpenStreetMap data from Geofabrik and other providers.
* [osmplotr](https://github.com/ropensci/osmplotr) - Data visualisation using OpenStreetMap objects.
* [osrm R](https://github.com/rCarto/osrm) - Interface Between R and the OpenStreetMap-Based Routing Service OSRM.
* [pastecs](https://cran.r-project.org/web/packages/pastecs/index.html) - Regulation, decomposition and analysis of space-time series.
* [PBSmapping](https://cran.r-project.org/web/packages/PBSmapping/index.html) - Mapping Fisheries Data and Spatial Analysis Tools.
* [PBSmodelling](https://cran.r-project.org/web/packages/PBSmodelling/index.html) - Provides modelling support.
* [pepair](https://github.com/dickoa/prepair) - An R package to repair broken GIS polygons using the prepair cpp library.
* [phenofit](https://github.com/kongdd/phenofit) - A state-of-the-art Vegetation Phenology extraction package.
* [phenopix](https://cran.r-project.org/web/packages/phenopix/index.html) - A collection of functions to process digital images, depict greenness index trajectories and extract relevant phenological stages.
* [plotGoogleMaps](https://cran.r-project.org/web/packages/plotGoogleMaps/index.html) - Interactive plot device for handling the geographic data for web browsers.
* [plotKML](https://cran.r-project.org/web/packages/plotKML/index.html) - Visualization of Spatial and Spatio-Temporal Objects in Google Earth.
* [polyclip](https://github.com/baddstats/polyclip) - R package polyclip: a port of the Clipper library for polygon geometry.
* [popRF](https://github.com/wpgp/popRF) - Random Forest-informed Population Disaggregation.
* [potential](https://github.com/riatelab/potential) - An R package to compute the potential model as defined by Stewart (1941).
* [PReMiuM](https://cran.r-project.org/web/packages/PReMiuM/index.html) - Dirichlet Process Bayesian Clustering, Profile Regression.
* [Prioritizr](https://github.com/prioritizr/prioritizr) - The prioritizr R package uses integer linear programming (ILP) techniques to provide a flexible interface for building and solving conservation planning problems.
* [ProbitSpatial](https://cran.r-project.org/web/packages/ProbitSpatial/index.html) - Binomial Spatial Probit models for big data.
* [quickglobe](https://github.com/daranzolin/quickglobe) - View Country Data via a 3D, D3, Globe.
* [r5r](https://github.com/ipeaGIT/r5r) - Package for rapid realistic routing on multimodal transport networks (walk, bike, public transport and car).
* [RandomFields](https://cran.r-project.org/web/packages/RandomFields/index.html) - Methods for the inference on and the simulation of Gaussian fields are provided, as well as methods for the simulation of extreme value random fields.
* [rangeMapper](https://cran.r-project.org/web/packages/rangeMapper/index.html) - Tools for easy generation of (life-history) traits maps based on species range (extent-of-occurrence) maps.
* [ranger](https://github.com/imbs-hl/ranger) - A Fast Implementation of Random Forests.
* [RArcInfo](https://cran.r-project.org/web/packages/RArcInfo/index.html) - Functions to import data from Arc/Info V7.x binary coverages.
* [raster](https://cran.r-project.org/web/packages/raster/raster.pdf) - Reading, writing, manipulating, analyzing and modeling of gridded spatial data.
* [rasterdiv](https://github.com/mattmar/rasterdiv) - Diversity Indices for Numerical Matrices.
* [rasterDT](https://github.com/JoshOBrien/rasterDT) - rasterDT uses the fast indexing, aggregation, and assignment operations provided by data.table to power speedy alternatives to several raster package functions.
* [rasterVis](https://cran.r-project.org/web/packages/rasterVis/index.html) - Visualization Methods for Raster Data.
* [rayshader](https://github.com/tylermorganwall/rayshader) - rayshader is an open source R package for producing 2D and 3D hillshaded maps of elevation matrices using a combination of raytracing, spherical texture mapping, and ambient occlusion.
* [rayvista](https://github.com/h-a-graham/rayvista) - A package to view a 3D scene anywhere on earth.
* [Rcitrus](http://www.leg.ufpr.br/Rcitrus/) - Spatial analysis of plant disease incidence.
* [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html) - Provides color schemes for maps and other graphics.
* [recmap](https://cran.r-project.org/web/packages/recmap/index.html) - Package provides rectangular cartograms with rectangle sizes reflecting for example population
* [regress](https://cran.r-project.org/web/packages/regress/index.html) - Functions to fit Gaussian linear model by maximising the residual log likelihood where the covariance structure can be written as a linear combination of known matrices.
* [rgdal](https://cran.r-project.org/web/packages/rgdal/index.html) - Bindings for the Geospatial Data Abstraction Library.
* [rgee](https://github.com/r-spatial/rgee) - Google Earth Engine for R.
* [rgeoda](https://github.com/GeoDaCenter/rgeoda) - rgeoda is a R package for spatial data analysis based on libgeoda and GeoDa.
* [rgeos](https://cran.r-project.org/web/packages/rgeos/index.html) - Interface to Geometry Engine - Open Source (GEOS) using the C API for topology operations on geometries.
* [Rgooglemaps](https://cran.r-project.org/web/packages/RgoogleMaps/index.html) - Overlays on Google map tiles in R.
* [rgrass7](https://cran.r-project.org/web/packages/rgrass7/index.html) - Interface Between GRASS 7 GIS and R.
* [rHarmonics](https://github.com/MBalthasar/rHarmonics/) - R package for harmonic modelling of time-series data.
* [ribge](https://github.com/tbrugz/ribge) - R package for (down)loading data from IBGE (Instituto Brasileiro de Geografia e Estatística).
* [rnaturalearth](https://github.com/ropensci/rnaturalearth) - An R package to hold and facilitate interaction with Natural Earth map data.
* [Rnetcdf](https://cran.r-project.org/web/packages/RNetCDF/index.html) - Interface to NetCDF Datasets.
* [rnoaa](https://github.com/ropensci/rnoaa) - R interface to many NOAA data sources.
* [RODBC](https://cran.r-project.org/web/packages/RODBC/index.html) - ODBC Database Access.
* [ROSM](https://github.com/paleolimbot/rosm) - Plot Open Street Map and Other Tiles in R.
* [RPyGeo](https://cran.r-project.org/web/packages/RPyGeo/index.html) - ArcGIS Geoprocessing in R via Python.
* [RQGIS](https://cran.r-project.org/web/packages/RQGIS/index.html) - Establishes an interface between R and QGIS.
* [RSAGA](https://cran.r-project.org/web/packages/RSAGA/index.html) - SAGA Geoprocessing and Terrain Analysis in R.
* [Rsagacmd](https://github.com/stevenpawley/Rsagacmd) - A package for linking R with the open-source SAGA-GIS.
* [rsMove](https://cran.r-project.org/web/packages/rsMove/index.html) - Tools that support the combined use of animal movement and remote sensing data.
* [rstac](https://github.com/brazil-data-cube/rstac) - R Client Library for SpatioTemporal Asset Catalog.
* [RStoolbox](https://cran.r-project.org/web/packages/RStoolbox/index.html) - Toolbox for remote sensing image processing and analysis such as calculating spectral indices, principal component transformation, unsupervised and supervised classification or fractional cover analyses.
* [rtsVis](https://github.com/JohMast/rtsVis) - A lightweight R package to visualize large raster time series, building on a fast temporal interpolation core.
* [rworldmap](https://cran.r-project.org/web/packages/rworldmap/index.html) - Mapping Global Data.
* [s2](https://github.com/spatstat/s2) - R bindings for Google's s2 library for geometry on the sphere.
* [S2sls](https://cran.r-project.org/web/packages/S2sls/index.html) - Fit a spatial instrumental-variable regression by two-stage least squares.
* [sf](https://github.com/r-spatial/sf) - Simple Features for R.
* [sfarrow](https://wcjochem.github.io/sfarrow/index.html) - Package for reading and writing Parquet and Feather files with sf objects using arrow in R.
* [sfheaders](https://github.com/dcooley/sfheaders) - Build sf objects from R and Rcpp.
* [sfnetworks](https://github.com/luukvdmeer/sfnetworks) - Tidy Geospatial Networks in R.
* [sftrack](https://github.com/mablab/sftrack) - Modern classes for tracking and movement data.
* [sgeostat](https://cran.r-project.org/web/packages/sgeostat/index.html) - An Object-oriented Framework for Geostatistical Modeling in S+ containing functions for variogram estimation, variogram fitting and kriging as well as some plot functions.
* [shapefiles](https://cran.r-project.org/web/packages/shapefiles/index.html) - Read and Write ESRI Shapefiles.
* [siplab](https://cran.r-project.org/web/packages/siplab/index.html) - A platform for experimenting with spatially explicit individual-based vegetation models.
* [sits](https://github.com/e-sensing/sits) - Satellite image time series package for R.
* [smacpod](https://cran.r-project.org/web/packages/smacpod/index.html) - Various statistical methods for analyzing case-control point data.
* [smerc](https://cran.r-project.org/web/packages/smerc/index.html) - Provides statistical methods for the analysis of data areal data, with a focus on cluster detection.
* [soilDB](https://github.com/ncss-tech/soilDB) - Simplified Access to NCSS Soil Databases.
* [sp](https://cran.r-project.org/web/packages/sp/index.html) - Classes and Methods for Spatial Data.
* [spacetime](https://cran.r-project.org/web/packages/spacetime/index.html) - Classes and Methods for Spatio-Temporal Data.
* [spacom](https://cran.r-project.org/web/packages/spacom/index.html) - Provides tools to construct and exploit spatially weighted context data.
* [spaMM](https://cran.r-project.org/web/packages/spaMM/index.html) - Inference in mixed-effect models, including generalized linear mixed models with spatial correlations and models with non-Gaussian random effects.
* [spanel](https://cran.r-project.org/web/packages/spanel/index.html) - Fit the spatial panel data models: the fixed effects, random effects and between models.
* [sparr](https://cran.r-project.org/web/packages/sparr/index.html) - Provides functions to estimate kernel-smoothed spatial and spatio-temporal densities and relative risk functions, and perform subsequent inference.
* [spatcounts](https://cran.r-project.org/web/packages/spatcounts/index.html) - Fit spatial CAR count regression models using MCMC.
* [spatgraphs](https://cran.r-project.org/web/packages/spatgraphs/index.html) - Graphs (or networks) and graph component calculations for spatial locations
* [spatialCovariance](https://cran.r-project.org/web/packages/spatialCovariance/index.html) - Supports the computation of spatial covariance matrices for data on rectangles.
* [SpatialEpi](https://cran.r-project.org/web/packages/SpatialEpi/index.html) - Methods and data for cluster detection and disease mapping.
* [SpatialPosition](https://cran.r-project.org/web/packages/SpatialPosition/index.html) - Computes spatial position models: Stewart potentials, Reilly catchment areas, Huff catchment areas.
* [spatialprobit](https://cran.r-project.org/web/packages/spatialprobit/index.html) - Bayesian Estimation of Spatial Probit and Tobit Models.
* [spatialRF](https://github.com/BlasBenito/spatialRF) - R package to fit spatial models with Random Forest.
* [SpatialRDD](https://github.com/axlehner/SpatialRDD) - R package to work spatialy with RDD files.
* [spatialsegregation](https://cran.r-project.org/web/packages/spatialsegregation/index.html) - Summaries for measuring segregation/mingling in multitype spatial point patterns with graph based neighbourhood description.
* [SpatialTools](https://cran.r-project.org/web/packages/SpatialTools/index.html) - Tools for spatial data analysis. Emphasis on kriging. Provides functions for prediction and simulation.
* [spatstat](https://cran.r-project.org/web/packages/spatstat/index.html) - Spatial Point Pattern Analysis, Model-Fitting, Simulation, Tests.
* [spatsurv](https://cran.r-project.org/web/packages/spatsurv/index.html) - Bayesian inference for parametric proportional hazards spatial survival models; flexible spatial survival models.
* [spBayesSurv](https://cran.r-project.org/web/packages/spBayesSurv/index.html) - Bayesian Modeling and Analysis of Spatially Correlated Survival Data.
* [spcosa](https://cran.r-project.org/web/packages/spcosa/index.html) - Spatial coverage sampling and random sampling from compact geographical strata created by k-means.
* [spdep](https://cran.r-project.org/web/packages/spdep/index.html) - Spatial Dependence: Weighting Schemes, Statistics and Models.
* [sperrorest](https://cran.r-project.org/web/packages/sperrorest/index.html) - Implements spatial error estimation and permutation-based variable importance measures for predictive models using spatial cross-validation and spatial block bootstrap.
* [spflow](https://github.com/LukeCe/spflow) - Spatial Econometric Interaction Models in R.
* [spind](https://cran.r-project.org/web/packages/spind/index.html) - Functions for spatial methods based on generalized estimating equations (GEE) and wavelet-revised methods (WRM), functions for scaling by wavelet multiresolution regression (WMRR), conducting multi-model inference, and stepwise model selection.
* [splancs](https://cran.r-project.org/web/packages/splancs/index.html) - Spatial and Space-Time Point Pattern Analysis.
* [splm](https://cran.r-project.org/web/packages/splm/index.html) - ML and GM estimation and diagnostic testing of econometric models for spatial panel data.
* [spmoran](https://cran.r-project.org/web/packages/spmoran/index.html) - Functions for estimating fixed and random effects eigenvector spatial filtering models.
* [spselect](https://cran.r-project.org/web/packages/spselect/index.html) - Fits spatial scale (SS) forward stepwise regression, SS incremental forward stagewise regression, SS least angle regression (LARS), and SS lasso models.
* [spsurvey](https://cran.r-project.org/web/packages/spsurvey/index.html) - Provides a range of sampling functions.
* [spTimer](https://cran.r-project.org/web/packages/spTimer/index.html) - Fits, spatially predicts and temporally forecasts large amounts of space-time data.
* [SSN](https://cran.r-project.org/web/packages/SSN/index.html) - Spatial statistical modeling and prediction for data on stream networks, including models based on in-stream distance.
* [starma](https://cran.r-project.org/web/packages/starma/index.html) - Statistical functions to identify, estimate and diagnose a Space-Time AutoRegressive Moving Average (STARMA) model.
* [stars](https://github.com/r-spatial/stars) - Spatiotemporal tidy arrays for R.
* [stlnpp](https://github.com/Moradii/stlnpp) - Spatio-temporal point patterns on linear networks.
* [stplanr](https://github.com/ropensci/stplanr) - Sustainable transport planning with R.
* [streetscape](https://github.com/land-info-lab/streetscape) - A collection of functions to search and download Mapillary street view images and to extract, quantify, and visualize visual features.
* [supercells](https://github.com/Nowosad/supercells) - The goal of supercells is to utilize the concept of superpixels to a variety of spatial data.
* [Tanaka](https://github.com/riatelab/tanaka) - Tanaka Maps with R.
* [taRifx](https://cran.r-project.org/web/packages/taRifx/index.html) - A collection of various utility and convenience functions.
* [teamlucc](https://github.com/azvoleff/teamlucc) -  Is designed to facilitate analysis of land use and cover change (LUCC) around the monitoring sites of the Tropical Ecology Assessment and Monitoring (TEAM) Network.
* [terra](https://github.com/rspatial/terra) - terra is an R package that replaces raster. It has a very similar, but simpler, interface, and it is much faster.
* [tgp](https://cran.r-project.org/web/packages/tgp/index.html) - Bayesian nonstationary, semiparametric nonlinear regression and design by treed Gaussian processes (GPs) with jumps to the limiting linear model (LLM).
* [tidync](https://github.com/hypertidy/tidync) - Systematic approaches to NetCDF data extraction, manipulation and visualization.
* [tidytransit](https://github.com/r-transit/tidytransit) - 'sf'-compatible package to analyze transit schedules, routes, and stops.
* [tiff](https://github.com/s-u/tiff) - Read and write TIFF images in R.
* [tmap](https://github.com/mtennekes/tmap) - R-library for drawing thematic maps. The API is based on A Layered Grammar of Graphics and resembles the syntax of ggplot2.
* [tmaptools](https://github.com/mtennekes/tmaptools) - This package offers a set of handy tool functions for reading and processing spatial data.
* [trip](https://cran.r-project.org/web/packages/trip/index.html) - Extends sp classes to permit the accessing and manipulating of spatial data for animal tracking.
* [tripack](https://cran.r-project.org/web/packages/tripack/index.html) - A constrained two-dimensional Delaunay triangulation package providing both triangulation and generation of voronoi mosaics of irregular spaced data.
* [tripEstimation](https://cran.r-project.org/web/packages/tripEstimation/index.html) - Data handling and estimation functions for animal movement estimation from archival or satellite tags.
* [uavRst](https://github.com/gisma/uavRst) - UAV related Remote Sensing Toolbox.
* [vapour](https://github.com/hypertidy/vapour) - A lightweight GDAL API package for R.
* [vec2dtransf](https://cran.r-project.org/web/packages/vec2dtransf/index.html) - Package for applying affine and similarity transformations on vector spatial data (sp objects).
* [vegan](https://cran.r-project.org/web/packages/vegan/index.html) - Ordination methods, diversity analysis and other functions for community and vegetation ecologists.
* [viewscape](https://github.com/land-info-lab/viewscape) - The viewscape package provides an accessible method of carrying out landscape spatial analysis based on the viewshed within the R environment
* [Watersheds](https://cran.r-project.org/web/packages/Watersheds/index.html) - Methods for watersheds aggregation and spatial drainage network analysis.
* [whiteboxR](https://github.com/giswqs/whiteboxR) - R frontend of [WhiteboxTools](https://github.com/jblindsay/whitebox-tools).
* [wordcloud2](https://github.com/Lchiffon/wordcloud2) - R interface to wordcloud for data visualization.
* [wt](https://github.com/paleolimbot/wk) - Lightweight Well-Known Geometry Parsing.

## Ruby

* [Agroclimatology](https://github.com/beaorn/agroclimatology) - Ruby client for interacting with the NASA (POWER) Agroclimatology Web Resource.
* [Evapotranspiration](https://github.com/beaorn/evapotranspiration) - Ruby library for calculating reference crop evapotranspiration (ETo).
* [ffi-geos](https://github.com/dark-panda/ffi-geos) - Low-level ruby bindings to GEOS library.
* [Geokit](https://github.com/geokit/geokit) - A Ruby gem & Rails plugin for easier map-based applications.
* [Mongoid Geospatial](https://github.com/nofxx/mongoid-geospatial) - A Mongoid Extension that simplifies the use of MongoDB spatial features.
* [PostGIS ActiveRecord Adapter](https://github.com/rgeo/activerecord-postgis-adapter) - ActiveRecord adapter for PostGIS.
* [Rgeo GeoJSON](https://github.com/rgeo/rgeo-geojson) - RGeo component for reading and writing GeoJSON.
* [Rgeo Shapefile](https://github.com/rgeo/rgeo-shapefile) - Optional module for RGeo for reading geospatial data from ESRI shapefiles.
* [Rgeo](https://github.com/rgeo/rgeo) - RGeo is a geospatial data library for Ruby. It provides an implementation of the Open Geospatial Consortium's Simple Features Specification
* [Ruby Geocoder](http://www.rubygeocoder.com/) - Integration with geocoding services.
* [ruby_postal](https://github.com/openvenues/ruby_postal) - Ruby bindings to libpostal for fast international address parsing/normalization.
* [SpatiaLite ActiveRecord Adapter](https://github.com/rgeo/activerecord-spatialite-adapter) - ActiveRecord adapter for Spatialite.


## Rust

* [A/B Street](https://github.com/dabreegster/abstreet) - A traffic simulation game exploring how small changes to roads affect cyclists, transit users, pedestrians, and drivers.
* [geoarrow-rs](https://github.com/kylebarron/geoarrow-rs) - GeoArrow in Rust and WebAssembly with vectorized geometry operations.
* [geographiclib-rs](https://github.com/georust/geographiclib-rs) - A subset of geographiclib implemented in Rust.
* [Hecate](https://github.com/mapbox/Hecate) - Fast Geospatial Feature Storage API.
* [kdtree-rs](https://github.com/mrhooray/kdtree-rs) - K-dimensional tree in Rust for fast geospatial indexing and nearest neighbors lookup.
* [maplibre-rs](https://github.com/maplibre/maplibre-rs) - About Native Maps for Web, Mobile and Desktop.
* [Martin](https://github.com/urbica/martin) - Martin is a PostGIS vector tiles server suitable for large databases. Martin is written in Rust using Actix web framework.
* [rgeometry](https://github.com/rgeometry/rgeometry) - Computational Geometry library written in Rust.
* [rstar](https://github.com/georust/rstar) - R*-tree library for the rust ecosystem.
* [rust-gdal](https://github.com/georust/rust-gdal) - Rust bindings for GDAL.
* [rust-geo](https://github.com/georust/rust-geo) - Geospatial primitives and algorithms for Rust.
* [rust-geocoding](https://github.com/georust/rust-geocoding) - Geocoding library for Rust.
* [rust-geohash](https://github.com/georust/rust-geohash) - Geohash for Rust.
* [rust-geojson](https://github.com/georust/rust-geojson) - Library for serializing the GeoJSON vector GIS file format.
* [rust-geos](https://github.com/georust/geos) - Rust bindings for GEOS C API.
* [rust-kml](https://github.com/georust/kml) - Rust support for reading and writing KML with a focus on conversion to geo-types primitives.
* [rust-gpx](https://github.com/georust/rust-gpx) - Rust read/write support for GPS Exchange Format (GPX).
* [rust-netcdf](https://github.com/georust/netcdf) - Medium-level netCDF bindings for Rust, allowing easy reading and writing of array-like structures to a file.
* [rust-osm](https://github.com/georust/rust-osm) - OSM XML serialization and other OpenStreetMap utilities.
* [rust-polyline](https://github.com/georust/rust-polyline) - Google Encoded Polyline encoding & decoding in Rust.
* [rust-postal](https://github.com/kodemartin/rustpostal) - Rust bindings to libpostal.
* [rust-proj](https://github.com/georust/rust-proj) - Rust bindings for Proj.
* [rust-shapefile](https://github.com/tmontaigu/shapefile-rs) - Rust read/write support for shapefiles.
* [rust-tilejson](https://github.com/georust/tilejson) - tilejson is a crate for serializing/deserializing the TileJSON format.
* [rust-topojson](https://github.com/georust/rust-topojson) - TopoJSON bindings and utilities for Rust.
* [rust-wkt](https://github.com/georust/rust-wkt) - Rust read/write support for well-known text (WKT).
* [WhiteboxTools](https://github.com/jblindsay/whitebox-tools) - An advanced geospatial data analysis platform.

## Scala

* [Franklin](https://github.com/azavea/franklin) - A STAC/OGC API Features Web Service.
* [fulgurite](https://github.com/SatelliteApplicationsCatapult/fulgurite) - Fulgurite is a way to use Apache Spark to process GeoTIFF images in a distributed way.
* [geoscript.scala](https://github.com/dwins/geoscript.scala) - Scala implementation of the GeoScript API.
* [GeoTrellis](https://github.com/locationtech/geotrellis) - GeoTrellis is a Scala library and framework that uses Spark to work with raster data.
* [mapnik2geotools](https://github.com/dwins/mapnik2geotools) - Using the Scala XML API to translate from Mapnik XML to GeoTools' SLD dialect.
* [osm4scala](https://simplexspatial.github.io/osm4scala/) - High perfromance Scala library and Spark Polyglot (Scala, Python, SQL, etc.) connector for OpenStreetMap Pbf files.
* [RTree2D](https://github.com/plokhotnyuk/rtree2d) - RTree2D is a 2D immutable R-tree with STR (Sort-Tile-Recursive) packing for ultra-fast nearest and intersection queries.
* [Stac4s](https://github.com/azavea/stac4s) - a scala library with primitives to build applications using the SpatioTemporal Asset Catalogs specification.

## Swift

* [Apple MapKit](https://developer.apple.com/documentation/mapkit) - Display map or satellite imagery directly from your app's interface, call out points of interest, and determine placemark information for map coordinates.
* [GEOSwift](https://github.com/GEOSwift/GEOSwift) - The Swift Geographic Engine.
* [Mapbox Navigation SDK for iOS](https://github.com/mapbox/mapbox-navigation-ios) - Turn-by-turn navigation logic and UI in Swift or Objective-C on iOS.
* [MapboxDirections.swift](https://github.com/mapbox/MapboxDirections.swift) - Traffic-aware directions in Swift or Objective-C on iOS, macOS, tvOS, and watchOS.
* [turf-swift](https://github.com/mapbox/turf-swift) - A Swift language port of Turf.js.

## Mobile Development

* [Apple MapKit](https://developer.apple.com/documentation/mapkit) - Display map or satellite imagery directly from your app's interface, call out points of interest, and determine placemark information for map coordinates.
* [flutter_map](https://github.com/fleaflet/flutter_map) - A Dart implementation of Leaflet for Flutter apps.
* [Google Maps API for Android](https://developers.google.com/maps/android/) - Google maps for Android.
* [Google Maps API for iOS](https://developers.google.com/maps/ios/) - Google maps for iOS.
* [Mapbox Android SDK](https://www.mapbox.com/android-sdk/) - An open source toolset for building mapping applications for Android devices.
* [Mapbox iOS SDK](https://www.mapbox.com/ios-sdk/) - An open source toolset for building mapping applications for iPhone and iPad devices.
* [mapbox-navigation-android](https://github.com/mapbox/mapbox-navigation-android) - Mapbox Navigation SDK for Android.
* [MapLibre GL Native](https://github.com/maplibre/maplibre-gl-native) - The open-source alternative to Mapbox GL Native. SDKs for iOS, Android and other platforms
* [MAPS.ME](https://github.com/mapsme/omim) - MAPS.ME — Offline OpenStreetMap maps for iOS and Android.
* [Nutiteq Maps SDK](https://github.com/nutiteq) - C++ maps library for iOS, Android, Windows Phone and Xamarin with bindings for Java, ObjectiveC and C#.
* [Organic Maps](https://github.com/organicmaps/organicmaps) - Organic Maps is a better fork of MAPS.ME, an Android & iOS offline maps app for travelers, tourists, hikers, and cyclists based on top of crowd-sourced OpenStreetMap data and curated with love by MAPS.ME founders. No ads, no tracking, no data collection, no crapware.
* [WhirlyGlobe/Maply](http://mousebird.github.io/WhirlyGlobe/) - Objective C code that is able to read and render vector tiles(and style with mapnik xml) on iOS devices.
* [XaMaps](https://github.com/AlexPshul/XaMaps) - Xamarin + Azure Maps.
* [XFAzureMapTrials](https://github.com/Druffl3/XFAzureMapTrials) - Use Azure Maps REST APIs with Xamarin.Forms.


## Geospatial Big Data

* [Apache Sedona](https://sedona.apache.org/latest-snapshot/) - Cluster computing system for processing large-scale spatial data
* [geobeam](https://github.com/GoogleCloudPlatform/dataflow-geobeam) - geobeam adds GIS capabilities to your Apache Beam pipelines and enables you to ingest and analyze massive amounts of geospatial data in parallel using Dataflow.
* [GeoMesa](https://github.com/locationtech/geomesa) - GeoMesa is a suite of tools for working with big geo-spatial data in a distributed fashion.
* [GeoTrellis](https://github.com/locationtech/geotrellis) - GeoTrellis is a geographic data processing engine for high performance applications.
* [GeoWave](https://github.com/locationtech/geowave) - GeoWave provides geospatial and temporal indexing on top of Accumulo and HBase.
* [Google Earth Engine](https://earthengine.google.com/) - Is a cloud computing platform for processing satellite imagery and other Earth observation data.


## Visualization

* [Blender GIS](https://github.com/domlysz/BlenderGIS) - Blender addons to make the bridge between Blender and geographic data.
* [bv](https://github.com/daleroberts/bv) - bv is a small tool to quickly view high-resolution multi-band imagery directly in your iTerm 2.
* [Cinder](https://libcinder.org/) - Cinder is a free and open source library for professional-quality creative coding in C++.
* [circlize](https://github.com/jokergoo/circlize) - Circular visualization in R. Circular layout is an efficient way for the visualization of huge amounts of information.
* [CityEngine-Twitter](https://github.com/urschrei/CityEngine-Twitter) - Visualise Twitter activity using a procedurally-generated 3D city model.
* [CometTS](https://github.com/CosmiQ/CometTS) - Comet Time Series Toolset for working with a time-series of remote sensing imagery and user defined polygons.
* [D3.js](https://d3js.org/) - D3.js is a JavaScript library for manipulating documents based on data.
* [Folium](https://github.com/python-visualization/folium) - Python Data. Leaflet.js Maps.
* [GeoJs](https://github.com/OpenGeoscience/geojs) - High-performance visualization and interactive data exploration of scientific and geospatial location aware datasets.
* [geoplot](https://github.com/ResidentMario/geoplot) -  High-level Python geospatial plotting library. It's an extension to cartopy and matplotlib which makes mapping easy.
* [GeoViews](https://github.com/holoviz/geoviews) - GeoViews is a Python library that makes it easy to explore and visualize any data that includes geographic locations.
* [Go Cart](https://github.com/Flow-Based-Cartograms/go_cart) - Fast cartogram generator written in C.
* [Kongsberg Geospatial's TerraLens SDK](https://www.kongsberggeospatial.com/products/terralens) - SDK designed for easy project integration and quick implementation in virtually any development environment. TerraLens provides real-time 2D and 3D mapping with powerful data visualization tools.
* [Kosmtik](https://github.com/kosmtik/kosmtik) - Very lite but extendable mapping framework to create Mapnik ready maps with OpenStreetMap data (and more).
* [mapdeck](https://github.com/SymbolixAU/mapdeck) - R interface to Deck.gl and Mapbox.
* [mplleaflet](https://github.com/jwass/mplleaflet) - Easily convert matplotlib plots from Python into interactive Leaflet web maps.
* [openFrameworks](http://openframeworks.cc/) - openFrameworks is an open source C++ toolkit for creative coding.
* [P5.js](https://p5js.org/) - Javascript library that starts with the original goal of Processing.
* [Peak map](https://github.com/anvaka/peak-map) - Allows you to visualize elevation of any area on the map with filled area charts.
* [PlotJuggler](https://github.com/facontidavide/PlotJuggler) - PlotJuggler is a tool to visualize time series that is fast, powerful and intuitive.
* [PostGIS Preview](https://github.com/NYCPlanning/labs-postgis-preview) - A lightweight node api and frontend for quickly previewing PostGIS queries.
* [procedural-gl-js](https://github.com/felixpalmer/procedural-gl-js) - Procedural GL JS is a library for creating 3D map experiences on the web, written in JavaScript and WebGL. It is built on top THREE.js.
* [Processing.py](http://py.processing.org/) - Python mode for Processing.
* [Processing](https://processing.org/) - Processing is a flexible software sketchbook and a language for learning how to code within the context of the visual arts.
* [Skia](https://skia.org/) - Skia is a complete 2D graphic library for drawing Text, Geometries, and Images.
* [Strava](https://github.com/marcusvolz/strava) - Create artistic visualisations with your exercise data.
* [three.js](https://threejs.org/) - A javascript 3D library which makes WebGL simpler
* [tippecanoe](https://github.com/mapbox/tippecanoe) - Build vector tilesets from large collections of GeoJSON features.
* [xarray_leaflet](https://github.com/davidbrochart/xarray_leaflet) - An xarray extension for tiled map plotting.


## Tools

* [52North SOS](http://52north.org/communities/sensorweb/sos/) - A reference implementation of the [OGC Sensor Observation Service specification (version 2.0)]
* [CODA](http://stcorp.github.io/coda/doc/html/index.html) - The Common Data Access toolbox (CODA) provides a set of tools for ingesting, processing, and analyzing remote sensing data.
* [DataPillager](https://github.com/gdherbert/DataPillager) - Download data from Esri service.
* [DroneDB](https://github.com/DroneDB/DroneDB) - Effortless aerial data management and sharing.
* [DsgTools](https://github.com/dsgoficial/DsgTools) - DSGTools is a QGIS plugin that allow users to create and manipulate Geospatial Data according to Brazilian Law (ET-EDGV 2.1.3 and ET-EDGV 3.0)
* [exactextract](https://github.com/isciences/exactextract) - Provides a fast and accurate algorithm for summarizing values in the portion of a raster dataset that is covered by a polygon, often referred to as zonal statistics.
* [fresco](https://github.com/go-spatial/fresco) - Fresco is an open source Mapbox Vector Tile Style editor that allows cartographers to craft stylesheets for use with Mapbox GL maps.
* [Galileo](https://galileo.gisdata.io/) - Geospatial data discovery and management platform. Search over 1,890+ data sources using advanced filters, spatial search, and previews. Manage your data with collections and downloads to 5 file types.
* [gdal-mini](https://github.com/rouault/gdal-mini) - Minimal version of GDAL.
* [Generic Mapping Tools](https://github.com/GenericMappingTools/gmt) - GMT is an open source collection of about 90 command-line tools for manipulating geographic and Cartesian data sets.
* [GeoGig](http://geogig.org/) - GeoGig is a Distributed Version Control System (DVCS) specially designed to handle geospatial data efficiently.
* [GISWATER](https://www.giswater.org/?lang=en) - Open-source software for water cycle management (water supply and urban drainage).
* [GrADS](http://cola.gmu.edu/grads/) - The Grid Analysis and Display System (GrADS) is an interactive desktop tool that is used for easy access, manipulation, and visualization of earth science data.
* [imscript](https://github.com/mnhrdt/imscript) - A collection of small and standalone utilities for image processing.
* [Kart](https://kartproject.org/) - Distributed version-control
for geospatial and tabular data.
* [Kongsberg Geospatial's TerraLens SDK](https://www.kongsberggeospatial.com/products/terralens) - SDK designed for easy project integration and quick implementation in virtually any development environment. TerraLens provides real-time 2D and 3D mapping with powerful data visualization tools.
* [landsat-espa-util](https://github.com/loicdtx/landsat-espa-util) - Library for querying and ordering Landsat Surface Reflectance data via ESPA.
* [Magrit](https://github.com/riatelab/magrit) - Magrit is an online application for thematic mapping.
* [MapShaper](http://mapshaper.org/) - Tools for editing Shapefile, GeoJSON, TopoJSON and CSV files.
* [Maptiks](https://maptiks.com/) - Maptiks its a tool that provides in-depth user insights by tracking how visitors click, pan and zoom on your maps.
* [MapTiler Desktop](https://www.maptiler.com/desktop/) - Software for converting your data into fast zoomable maps. Load your image or geodata and get a tiled map.
* [Mapus](https://github.com/alyssaxuu/mapus) - Mapus is a tool to explore and annotate collaboratively on a map.
* [Open Location Code](https://github.com/google/open-location-code) - Open Location Code is a library to generate short codes, called "plus codes", that can be used as digital addresses where street addresses don't exist.
* [opensarkit](https://github.com/openforis/opensarkit) - Tools for Automatic Preprocessing of SAR Imagery.
* [Osm2pgsql](https://github.com/openstreetmap/osm2pgsql) - osm2pgsql is a tool for loading OpenStreetMap data into a PostgreSQL.
* [Planetiler](https://github.com/onthegomap/planetiler) - Flexible tool to build planet-scale vector tilesets from OpenStreetMap data in a few hours.
* [Projection  Wizard](http://projectionwizard.org/) - Helps you select an appropriate projection for your map, depending on the area that you are mapping.
* [sat-search](https://github.com/sat-utils/sat-search) - Sat-search is a Python 3 library and a command line tool for discovering and downloading publicly available satellite imagery using STAC compliant API.
* [Satellite Optical Sensor Calculator](https://opticalsatellitetools.space/) - A calculator that simplifies complex satellite sensor design by providing approximate calculations for optical parameters.
* [TileMill](https://tilemill-project.github.io/tilemill/) - TileMill is a modern map design studio powered by Node.js and Mapnik.
* [veins](https://github.com/sommer/veins) - Open source vehicular network simulation framework.
* [eodag](https://github.com/CS-SI/eodag) - Command line tool and a plugin-oriented Python framework for searching, aggregating results and downloading remote sensed images while offering a unified API for data access regardless of the data provider.
* [nextgisweb](https://github.com/nextgis/nextgisweb) - Server based application/server-side framework for geodata storage, management and visualization.


## Cheat sheets

* [Fiona-Rasterio-Shapely Cheat Sheet](https://github.com/sgillies/frs-cheat-sheet) - A cheat sheet for Fiona/Rasterio/Shapely command-line geodata tools.
* [GDAL](https://github.com/dwtkns/gdal-cheat-sheet) - Cheat sheet for GDAL/OGR command-line tools.
* [GNU Parallel](https://www.gnu.org/software/parallel/parallel_cheat.pdf) - Cheat sheet for the GNU Parallel CLI tool.
* [PostGIS 2](https://gist.github.com/kidpixo/5698476) - Cheat sheet for PostGIS (version 2)
* [PostGIS Raster](http://www.postgis.us/downloads/postgis20_raster_cheatsheet.pdf) - Cheat sheet for PostGIS Raster manipulation.
* [PostGIS](http://www.postgis.us/downloads/postgis21_cheatsheet.pdf) - Cheat sheet for PostGIS.

## Data Sources

* [AIforEarthDataSets](https://github.com/microsoft/AIforEarthDataSets) - Notebooks and documentation for AI-for-Earth-managed datasets on Azure Open Datasets.
* [ASTER Data](https://terra.nasa.gov/data/aster-data) - Download ASTER data.
* [Callisto Generated Datasets](https://github.com/Agri-Hub/Callisto-Dataset-Collection) - A list of datasets aiming to enable Artificial Intelligence applications that use Copernicus data.
* [CBERS on AWS](https://github.com/fredliporace/cbers-on-aws) - Information, tools and data related to the China-Brazil Earth Resources Satellite (CBERS) PDS on AWS.
* [Cityscapes Dataset](https://www.cityscapes-dataset.com/) -  large-scale dataset that contains a diverse set of stereo video sequences recorded in street scenes from 50 different cities, with high quality pixel-level annotations of 5 000 frames in addition to a larger set of 20 000 weakly annotated frames.
* [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/home) - Sentinel data from scihub.
* [RoadDetections](https://github.com/microsoft/RoadDetections) - Road detections from Microsoft Maps aerial imagery.
* [Geofabrik](http://download.geofabrik.de/) - This is another source of prepared OpenStreetMap data. This distribution is generally built nightly and comes in OSM XML, pbf, and shapefile (for very popular areas) formats.
* [GeoNames](http://www.geonames.org/) - The GeoNames geographical database covers all countries and contains over eight million place names (cities, postal codes, countries) that are available for download free of charge.
* [INPE Database](http://www.dgi.inpe.br/CDSR/) - Download free satellite data including MODIS, Landsat (1-8), ResourceSat (1-2) and CBERS (2 and 2B) data.
* [INPE CBERS4A and Amazonia1 Database](http://www2.dgi.inpe.br/catalogo/explore) - Download free CBERS 4A and Amazonia 1 images.
* [MapTiler Data](https://www.maptiler.com/data/) - Ready-to-use geographic data. The very best of open geospatial data, processed and packaged for your next on-prem project. Available as vector/raster tiles and in GIS formats.
* [Mapzen](https://mapzen.com/metro-extracts) - It provides data in OSM/PBF and Esri shapefile formats for popular cities.
* [Natural Earth](http://www.naturalearthdata.com/) - This site offers public domain map data sets that contain both raster and vector data.
* [Scale Open Datasets](https://scale.com/open-datasets?utm_campaign=Spatial%20Awareness&utm_medium=email&utm_source=Revue%20newsletter) - Open Datasets for Autonomous Driving.
* [Sentinel 2 AWS](http://sentinel-pds.s3-website.eu-central-1.amazonaws.com/) - Sentinel 2 data on Amazon S3.
* [TZ Timezone Shapefiles](http://efele.net/maps/tz/world/) - Polygon boundaries of world timezones.
* [USGS Earth Explorer](http://earthexplorer.usgs.gov/) - Provides online search,metadata export, and data download for earth science data from the archives of the USGS.


## Resources

* [Cartographical Map Projections](http://www.progonos.com/furuti/MapProj/Normal/TOC/cartTOC.html) - A good introduction to projected coordinate systems.
* [Cloud Optimized Point Cloud Specification](https://github.com/copcio/copcio.github.io) - Geospatial, compressed, range-readable, LAZ-compatible point cloud format.
* [ESRI Shapefile Specs](http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf) - Shapefile specifications.
* [GDAL/OGR Cookbook](https://pcjericks.github.io/py-gdalogr-cookbook/) - Simple code snippets on how to use the Python GDAL/OGR API.
* [GeoJSON.io](http://geojson.io/) - geojson.io is a quick, simple tool for creating, viewing, and sharing maps.
* [GeoParquet](https://github.com/opengeospatial/geoparquet) - Specification for storing geospatial vector data (point, line, polygon) in Parquet.
* [Geopython](https://github.com/urschrei/Geopython) - Notebooks and libraries for spatial/geo Python explorations.
* [GIGS](https://gigs.iogp.org/) - GIGS comprises qualitative test series checklists and quantitative test dataset files.
* [IndexDatabase](http://www.indexdatabase.de/) - A database for remote sensing indices.
* [LOLManuscriptMonday](https://github.com/ladiesoflandsat/LOLManuscriptMonday) - Hold the links to the Ladies of Landsat Manuscript Monday series.
* [Spatialreference.org](http://spatialreference.org/) - Source for coordinate system information.
* [TileJSON.io](http://tilejson.io/) - tilejson.io is a simple viewer for raster tile sets (Enter tile URL, layer properties, share).

## Free and Open Source Books

* [An Introduction to Spatial Data Analysis and Statistics: A Course in R](https://paezha.github.io/spatial-analysis-r/)
* [Cloud-Based Remote Sensing with Google Earth Engine](https://www.eefabook.org/)
* [Elegant and informative maps with tmap](https://r-tmap.github.io/tmap-book/)
* [Geocomputation with Python](https://py.geocompx.org/)
* [Geocomputation with R](https://r.geocompx.org/)
* [Geographic Data Science with Python](https://geographicdata.science/book/intro.html)
* [Geographic Data Science with R: Visualizing and Analyzing Environmental Change](https://bookdown.org/mcwimberly/gdswr-book/)
* [Geospatial Analysis](https://www.spatialanalysisonline.com/)
* [Geospatial Data Science with Julia](https://juliaearth.github.io/geospatial-data-science-with-julia/)
* [Google Earth Engine Applications](https://www.mdpi.com/books/reprint/1262-google-earth-engine-applications)
* [Intro to GIS and Spatial Analysis](https://mgimond.github.io/Spatial/index.html)
* [Introduction to Spatial Data Programming with R](https://geobgu.xyz/r/)
* [Introduction to urban accessibility: A practical guide with R](https://ipeagit.github.io/intro_access_book/)
* [R for Geographic Data Science](https://sdesabbata.github.io/r-for-geographic-data-science/index.html)
* [SAR Handbook - Comprehensive Methodologies for Forest Monitoring and Biomass Estimation](https://servirglobal.net/resources/sar-handbook)
* [Spatial Data Science With Applications in R](https://r-spatial.org/book/)
* [Spatial Microsimulation with R](https://spatial-microsim-book.robinlovelace.net/)
* [Spatial Modelling for Data Scientists](https://gdsl-ul.github.io/san/)
* [Spatial Statistics for Data Science: Theory and Practice with R](https://www.paulamoraga.com/book-spatial/index.html)
* [sits: Satellite Image Time Series Analysis on Earth Observation Data Cubes](https://e-sensing.github.io/sitsbook/)
* [The Language of Spatial Analisys](https://www.esri.com/content/dam/esrisites/sitecore-archive/Files/Pdfs/library/books/the-language-of-spatial-analysis.pdf)

## Conferences

* [ESRI User Conference](https://www.esri.com/en-us/about/events/uc/overview) - Esri International User Conference is an event dedicated to geographic information system technology.
* [FOSS4G](http://foss4g.org/) - Free and Open Source Software for Geospatial.
* [FOSSGIS](https://fossgis.de/) - Yearly conference of the German OpenStreetMap chapter and FOSS GIS community
* [Geo For Good Summit](https://earthoutreachonair.withgoogle.com/events/geoforgood21) - Annual conference, hosted by Google, geared toward nonprofits, scientists, government agencies and other change-makers who want to leverage mapping tools and technology for positive impact in the world.
* [GEOINFO](http://www.geoinfo.info/) - The GEOINFO series (Brazilian Symposium on Geoinformatics) is an annual conference for exploring ongoing research, development and innovative applications on geographic information science and related areas.
* [GeoPython](https://2021.geopython.net/) - The conference is focused on Python and Geo, its toolkits and applications.
* [International Syposium on Digital Earth](https://pcoconvin.eventsair.com/isde23/) - Event dedicated to bring together policy makers and scientists and will explore pathways towards the vision of a ‘Digital Earth
* [International Society for Photogrammetry and Remote Sensing](https://www.isprs2020-nice.com/) - The ISPRS Congress is the leading forum where classical and emergent topics related to photogrammetry, remote sensing, and spatial information sciences are discussed.
* [RCMRD International Conference](https://www.rcmrd.org/) - Annual conference held in Nairobi - Kenya, bringing together policymakers, executives, experts, researchers, developers, and innovators worldwide to exchange insights in Earth observation (EO) and Geographic Information System (GIS).
* [SBSR](https://2023.sbsr.com.br/) - Bi-annual Brazilian National Symposium on Remote Sensing.
* [Spatial Data Conference](https://spatial-data-science-conference.com/) -  Annual Conferece that intersects GIS, Advanced Analytics & Data Science that is growing rapidly & answering some of the most pressing questions in both the private & public sector.
* [State of the Map](https://stateofthemap.org/) - Annual event for all mappers and OpenStreetMap users.

## Podcasts

* [Down To Earth: A podcast for Geoscientists by Geoscientist](https://podcasts.apple.com/us/podcast/down-to-earth-a-podcast-for-geoscientists-by-geoscientist/id1549020890) - 30-minute podcast about innovative geoscience and the incredible people behind it. Each week, we host a different guest to talk about science, careers, and passions.
* [Eyes on Earth](https://www.usgs.gov/centers/eros/science/eyes-earth?qt-science_center_objects=0#qt-science_center_objects) - Eyes on Earth is a podcast on remote sensing, Earth observation, land change and science, brought to you by the USGS Earth Resources Observation and Science (EROS) Center.
* [ESRI & The Science of Where](https://www.esri.com/about/newsroom/podcast/) - Talks about business and technology leaders who share analysis, insights, and stories on data science, the Internet of Things, Smart Communities and other forces driving digital transformation and leveraging the power of location intelligence.
* [GIS Directions](https://esriaustralia.com.au/gis-directions-podcast) - Chat with inspiring GIS users, discuss new industry trends, and dish out plenty of practical pointers.
* [Geoadorable](https://geodorable.com/) - A podcast that may include anything and everything about the geospatial world. From news articles about the GIS industry that take our fancy, interviews with GIS practitioners, random acts of geospatial madness and of course the legendary game Export to Shapefile.
* [Geographical Thinking](https://www.esri.ca/en-ca/news-events/news/podcasts) - Tune in for inspiring stories from thought leaders and GIS users across business, government and education in Canada.
* [Geointeresting](https://podcasts.apple.com/us/podcast/geointeresting/id990858116) - Official podcast of the National Geospatial-Intelligence Agency. Geointeresting features conversations with innovators, explorers and pathfinders.
* [Geomob Podcast](https://thegeomob.com/podcast/) - weekly podcast interviewing anyone doing interesting things in geo, be it for fun or profit.
* [The MapScaping](https://mapscaping.com/blogs/the-mapscaping-podcast) - Weekly podcast featuring interesting people doing amazing work in the geospatial world.
* [Minds Behind Maps](https://minds-behind-maps.simplecast.com/) - Informal conversations with those creating maps, understanding how and why they build them. Earth Observation, Data Science, Business and how smart people combine them all to impact our world.
* [More Than Just Maps](https://urisatexas.org/podcast) - Talks with GIS veterans and geniuses who know a thing or two about how to find your way from student to professional and beyond, while also chatting about some neat tools, tricks, and trends. Presented by the URISA Texas Chapter.
* [Project Geospatial](https://www.projectgeospatial.com/) - Project Geospatial is a web series and blog dedicated to increasing awareness of Geospatial Technology, industry best practices, and GIS resources.
* [Scene From Above](https://scenefromabove.podbean.com/) - Earth observation, remote sensing, geospatial and geeky chat
* [A VerySpatial](https://veryspatial.com/) - A VerySpatial Podcast is your weekly source for information on Geography and geospatial technologies.


## References and other awesome lists

* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision)
* [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision)
* [Awesome DEM](https://github.com/DahnJ/Awesome-DEM) - Overview of Digital Elevation Model (DEM) datasets.
* [Awesome Earth Engine Apps](https://github.com/philippgaertner/awesome-earth-engine-apps)
* [Awesome Forests](https://github.com/blutjens/awesome-forests) - A curated list of ground-truth forest datasets for the machine learning and forestry community.
* [Awesome Frontend GIS](https://github.com/joewdavies/awesome-frontend-gis) - Geographic Information Systems (GIS) for web browsers. For managing, analyzing, editing, and visualizing geographic data.
* [Awesome Geo Rust](https://github.com/pka/awesome-georust)
* [Awesome GIS - sshuair](https://github.com/sshuair/awesome-gis)
* [Awesome Object Detection](https://github.com/amusi/awesome-object-detection)
* [Awesome Python](https://github.com/vinta/awesome-python/blob/master/README.md)
* [Awesome SAR](https://github.com/RadarCODE/awesome-sar)
* [Awesome Satellite Imagery Datasets](https://github.com/chrieke/awesome-satellite-imagery-datasets)
* [Awesome Semantic Segmentation](https://github.com/mrgloom/awesome-semantic-segmentation)
* [Awesome Sentinel](https://github.com/Fernerkundung/awesome-sentinel)
* [Awesome Spatial](https://github.com/RoboDonut/awesome-spatial/blob/master/README.md)
* [Awesome Spectral Indices](https://github.com/awesome-spectral-indices/awesome-spectral-indices)
* [Awesome SQLite](https://github.com/planetopendata/awesome-sqlite)
* [Awesome-EarthObservation-Code](https://github.com/acgeospatial/awesome-earthobservation-code)
* [Digital Earth Australia notebooks and tools repository](https://github.com/GeoscienceAustralia/dea-notebooks)
* [Cartography / Mapping / Web design resources](https://github.com/tolomaps/resources)
* [Essential Python Geospatial Libraries](http://carsonfarmer.com/2013/07/essential-python-geo-libraries/)
* [GeoJSON](https://github.com/tmcw/awesome-geojson)
* [GeoRails](http://daniel-azuma.com/articles/georails/)
* [JuliaGeo](https://juliageo.org/)
* [satellite-image-deep-learning](https://github.com/robmarkcole/satellite-image-deep-learning)
* [Spatial R](https://cran.r-project.org/web/views/Spatial.html)
* [Vector Tiles](https://github.com/mapbox/awesome-vector-tiles)
