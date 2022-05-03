### Lab03
#### Midnight Cookie return
This map shows the quickest path to Insomnia Cookies from the Belk Library in Boone, NC. I included markers for main building on the way to the shop as landmarks for reference. This was an assignment for my 3814 web-mapping class. My name is Feon Yelvington.

##### major functions
```html
onEachFeature : function(feature, layer) {
layer.bindTooltip(feature.properties['name']);
}
```
##### Libraries
[jquery](http://code.jquery.com/jquery-3.1.1.min.js)
[leaflet](https://unpkg.com/leaflet@1.0.1/dist/leaflet.js)

##### Map source
[leaflet provider](https://tiles.stadiamaps.com/tiles/alidade_smooth_dark/)
[google](https://goo.gl/maps/dcPaMqzKcKXWkBb76)

For some reason the map I orignally chose would not show in Github, so I change the basemap and route color. I added a png of what my orignal map looked like in atom as well. 
