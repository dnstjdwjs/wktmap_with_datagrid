# wktmap

Code for <https://wktmap.com>.

This page parses and visualizes [WKT](https://en.wikipedia.org/wiki/Well-known_text_representation_of_geometry) (ISO 13249) as well as [geo:wktLiteral](https://opengeospatial.github.io/ogc-geosparql/geosparql11/spec.html#_rdfs_datatype_geowktliteral) strings in a variety of coordinate reference systems. Built with [OpenLayers](https://openlayers.org/), [Leaflet](https://leafletjs.com/), [Proj4js](https://trac.osgeo.org/proj4js), and [epsg.io](https://epsg.io/).

# Adding datagrid
## goal
1. present geometric datas on clickable table 
2. copy wkt-string on existing wkt-textbox 
    from selected data on the table
3. data model and api call.