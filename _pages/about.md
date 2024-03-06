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


<iframe src="/talkmap/map.html" height="600" width="480" style="border:none;"></iframe>
<!DOCTYPE html>
<html>
    <head>
        <title>Snazzy Maps Super Simple Example</title>
        
        <style type="text/css">
            /* Set a size for our map container, the Google Map will take up 100% of this container */
            #map {
                width: 750px;
                height: 500px;
            }
        </style>
        
        <!-- 
            You need to include this script tag on any page that has a Google Map.

            The following script tag will work when opening this example locally on your computer.
            But if you use this on a localhost server or a live website you will need to include an API key. 
            Sign up for one here (it's free for small usage): 
                https://developers.google.com/maps/documentation/javascript/tutorial#api_key

            After you sign up, use the following script tag with YOUR_GOOGLE_API_KEY replaced with your actual key.
                <script type="text/javascript" src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_API_KEY"></script>
        -->
        <script type="text/javascript" src="https://maps.googleapis.com/maps/api/js"></script>
        
        <script type="text/javascript">
            // When the window has finished loading create our google map below
            google.maps.event.addDomListener(window, 'load', init);
        
            function init() {
                // Basic options for a simple Google Map
                // For more options see: https://developers.google.com/maps/documentation/javascript/reference#MapOptions
                var mapOptions = {
                    // How zoomed in you want the map to start at (always required)
                    zoom: 11,

                    // The latitude and longitude to center the map (always required)
                    center: new google.maps.LatLng(40.6700, -73.9400), // New York

                    // How you would like to style the map. 
                    // This is where you would paste any style found on Snazzy Maps.
                    styles: [{"featureType":"all","elementType":"geometry.fill","stylers":[{"weight":"2.00"}]},{"featureType":"all","elementType":"geometry.stroke","stylers":[{"color":"#9c9c9c"}]},{"featureType":"all","elementType":"labels.text","stylers":[{"visibility":"on"}]},{"featureType":"landscape","elementType":"all","stylers":[{"color":"#f2f2f2"}]},{"featureType":"landscape","elementType":"geometry.fill","stylers":[{"color":"#ffffff"}]},{"featureType":"landscape.man_made","elementType":"geometry.fill","stylers":[{"color":"#ffffff"}]},{"featureType":"poi","elementType":"all","stylers":[{"visibility":"off"}]},{"featureType":"road","elementType":"all","stylers":[{"saturation":-100},{"lightness":45}]},{"featureType":"road","elementType":"geometry.fill","stylers":[{"color":"#eeeeee"}]},{"featureType":"road","elementType":"labels.text.fill","stylers":[{"color":"#7b7b7b"}]},{"featureType":"road","elementType":"labels.text.stroke","stylers":[{"color":"#ffffff"}]},{"featureType":"road.highway","elementType":"all","stylers":[{"visibility":"simplified"}]},{"featureType":"road.arterial","elementType":"labels.icon","stylers":[{"visibility":"off"}]},{"featureType":"transit","elementType":"all","stylers":[{"visibility":"off"}]},{"featureType":"water","elementType":"all","stylers":[{"color":"#46bcec"},{"visibility":"on"}]},{"featureType":"water","elementType":"geometry.fill","stylers":[{"color":"#c8d7d4"}]},{"featureType":"water","elementType":"labels.text.fill","stylers":[{"color":"#070707"}]},{"featureType":"water","elementType":"labels.text.stroke","stylers":[{"color":"#ffffff"}]}]
                };

                // Get the HTML DOM element that will contain your map 
                // We are using a div with id="map" seen below in the <body>
                var mapElement = document.getElementById('map');

                // Create the Google Map using our element and options defined above
                var map = new google.maps.Map(mapElement, mapOptions);

                // Let's also add a marker while we're at it
                var marker = new google.maps.Marker({
                    position: new google.maps.LatLng(40.6700, -73.9400),
                    map: map,
                    title: 'Snazzy!'
                });
            }
        </script>
    </head>
    <body>
        <h1>Snazzy Maps Super Simple Example</h1>
        <h2><a href="https://snazzymaps.com/style/8097/wy" target="_blank">WY</a></h2>

        <!-- The element that will contain our Google Map. This is used in both the Javascript and CSS above. -->
        <div id="map"></div>
    </body>
</html>
