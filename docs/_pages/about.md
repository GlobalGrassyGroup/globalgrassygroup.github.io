---
permalink: /about/
layout: splash
hidden: true
header:
  overlay_image: /images/p2.jpg
  caption: "Photo credit: Caroline Lehmann"
excerpt: >
 Global Grassy Group<br />
---
<br>

Grassy biomes span ~40% of the global land surface. They are critical to livelihoods, economics, biodiversity and Earth System functioning. Across grassy biomes globally, the composition, structure and biomass of the ground layer vary as a product of antecedent rainfall, time of year, local conditions, disturbance and the history of human use. Appropriate management in the context of fire, animals and human use requires an understanding of the composition, structure and functioning of the ground layer.  These data are not always collected despite the ground layer and its constituent grasses and forbs, driving processes central to shaping the dynamics of these ecosystems. Lack of consistency in data stems from sites of varied size and organisation, and where plots variably record composition limiting the comparability and utility of data from different collection efforts.

***Globally Grassy Group*** (GGG) gathers ecologists and biologists aiming to standardise and improve vegetation sampling in the grassy biomes. On this website, you can find our suggested [sampling protocols](/protocol/), [resources](/resources/) needed for undertaking fieldwork, [GGG datasets](datasets) (and [publications](publications) that used these data), and many more. 

If you would like to contribute your data to GGG, please read our [participation guide]() and [contact us](/contact/).






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
	
