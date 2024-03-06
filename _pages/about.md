---
permalink: /
title: "That's me, who are you? :)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


GIS-ace from Freiburg im Breisgau, Germany, rocking tech and terrain! 🌍💻 
After his Geography B.Sc. @ Georg-August University Göttingen in 2019, Jan has been been working in a multinational team on the technical planning of linear infrastructure (overland and underground powerlines) for multiple major projects in Germany. From 2023 to the start of his Master's Degree in Okt 2023, Jan was working for hannIT, a public sector IT firm in Hannover where he, again, in a team, helped with the installation and maintaining of hard- and software components like apache servers, proprietary red hat software and ESRI ArcGIS Web-GIS-Services or custom desktop CAD workstations. Jan delivers! His tools? QGIS, MicroStation, and more. Languages? Fluent in German, English, and a touch of French. Hobbies? Diving under water and into codes. A multi-talent balancing between bits, trees, and stages. 🚀🌳🎤

With his deep understanding of Geographic Information Systems (GIS), he's become an indispensable force in the industry over recent years. Working at imp GmbH (part of SWECO AB) from 2020 to 2023, he gained extensive experience in the technical planning of linear infrastructure. Jan is not just an expert in using technical software like QGIS and MicroStation or TerraScan, but also in designing and executing complex projects. His skills extend beyond technical implementation to project management and client communication, ensuring the successful completion of complex projects. His passion for geography and technology, combined with his ability to work in multicultural teams and communicate his ideas clearly and effectively, makes him a valuable team member in any project.

Living in Hannover, a city known for its cultural diversity and innovation, perfectly matches his quest for continuous learning and adapting to new technologies. Besides his professional activities, he engages in the local tech community and music scene, sharing his knowledge and promoting exchange among professionals. His interests go well beyond his profession – from diving to music production, highlighting his creative vein and his ability to create and explore complex worlds.

+++++++++++


var map = L.map('map').setView([51.505, -0.09], 13);

L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
}).addTo(map);

L.marker([51.5, -0.09]).addTo(map)
    .bindPopup('A pretty CSS popup.<br> Easily customizable.')
    .openPopup();












<iframe
  width="600"
  height="450"
  style="border:0"
  loading="lazy"
  allowfullscreen
  referrerpolicy="no-referrer-when-downgrade"
  src="https://www.google.com/maps/embed/v1/place?key=API_KEY
    &q=Space+Needle,Seattle+WA">
</iframe>

++++++++++++++











#











<!DOCTYPE html>
<html>
<head>
    <title>Simple Leaflet Map</title>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
    <style>
        #map {
            height: 400px;
            width: 100%;
        }
    </style>
</head>
<body>

<div id="map"></div>

<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
<script>
    var map = L.map('map').setView([51.505, -0.09], 13); // Set view to [latitude, longitude], zoom level

    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
        attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors'
    }).addTo(map);

    // Adding a marker to the map at the same coordinates
    L.marker([51.505, -0.09]).addTo(map)
        .bindPopup('A pretty CSS3 popup.<br> Easily customizable.')
        .openPopup();
</script>

</body>
</html>







+++



Here is a button embedded in Markdown:

<button style="background-color: blue; color: white;">Click Me!</button>

Continue with regular Markdown text here.

<!DOCTYPE html>
<html>
<head>
    <title>Leaflet Map with Markers</title>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
    <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>

    <style>
        #map { height: 400px; }
    </style>
</head>
<body>

<div id="map"></div>

<script>
    var map = L.map('map').setView([52.37052, 9.73322], 6); // Set view to a center point between the two cities

    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
        attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
    }).addTo(map);

    // Marker for Hannover
    L.marker([52.37052, 9.73322]).addTo(map)
        .bindPopup('<b>Hannover</b>');

    // Marker for Freiburg im Breisgau
    L.marker([47.99901, 7.8421]).addTo(map)
        .bindPopup('<b>Freiburg im Breisgau</b>');
</script>

</body>
</html>


<iframe src="map.html" width="100%" height="400"></iframe>




<iframe src="/talkmap/map.html" height="600" width="480" style="border:none;"></iframe>

