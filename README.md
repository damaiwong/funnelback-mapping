# Funnelback mapping

This code implements map visualisation code for geospatial enabled Funnelback results.

It allows for easy deployment of results onto a map.

Provides: 
* a standardised way to integrating Funnelback search results with popular mapping services with minimal customisation.
* a default set of Freemarker macros to handle map presentation.
* flexibility in the choice of mapping service (eg. Google Maps vs. OpenStreetMap vs. Bing Maps) with minimal changes to code
* the ability to use custom pins, info boxes and pin clustering.
* a GeoJSON endpoint that can be accessed by other services

# Dependencies

The following third party code is used for this implementation:

* [Leaflet.js 1.0.1](http://leafletjs.com/download.html)
* [Leaflet.markercluster ](https://github.com/Leaflet/Leaflet.markercluster) - Marker clustering plugin
* [Leaflet.GridLayer.GoogleMutant](https://gitlab.com/IvanSanchez/Leaflet.GridLayer.GoogleMutant) - Implements mapping tile layers using services such as Google Maps and Open Street Map.
* [Leaflet.fullscreen](https://github.com/Leaflet/Leaflet.fullscreen)  - fullscreen control
* [Leaflet.Spin](https://github.com/makinacorpus/Leaflet.Spin) - spinner plugin
* [SpinJS](http://fgnass.github.io/spin.js/) - Javascript spinner
* [pLeaflet.Sleep](https://github.com/CliffCloud/Leaflet.Sleep) - deactivates the map so that it doesn't zoom when you scroll a page containing the map