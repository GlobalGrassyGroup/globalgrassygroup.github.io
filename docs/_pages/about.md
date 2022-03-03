---
permalink: /about/
layout: splash
---
<br>
We are a group of ecologists and biologists aiming to standardise and improve vegetation sampling in the grassy biomes.


<html>
<head>
  <title>A Leaflet map!</title>
  <link rel="stylesheet" href="./Leaflet-1.7.1/leaflet.css"/>
  <script src="./Leaflet-1.7.1/leaflet.js"></script>
  <style>
    #map{ height: 100% }
  </style>
</head>
<body>

  <div id="map"></div>

  <script>

  // initialize the map
  var map = L.map('map').setView([42.35, -71.08], 13);

  // load a tile layer
  L.tileLayer('http://tiles.mapc.org/basemap/{z}/{x}/{y}.png',
    {
      attribution: 'Tiles by <a href="http://mapc.org">MAPC</a>, Data by <a href="http://mass.gov/mgis">MassGIS</a>',
      maxZoom: 17,
      minZoom: 9
    }).addTo(map);

  </script>
</body>
</html>
	
