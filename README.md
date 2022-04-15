# ISS_API
Simple Project that plots an ISS to a map using leaflet.js and wheretheiss.at API

<h4>How It Works:</h4>
            <p>
                First i make a fetch request to get the data in the form of json using the API provided from <a
                    href="https://wheretheiss.at/">wheretheiss.at</a>.
                Then i use <a href="https://leafletjs.com/">leaflet.js</a> to draw the map to a HTML div element.
                After i draw the map, i make a use the marker class from the leafletjs library to plot a marker on the
                map
                at the latitude and longitude retrieved from wheretheiss.at.
                The marker is a custom drawn icon(i did my best to draw the ISS in pixel art :P) btw i use <a
                    href="https://www.aseprite.org/">aseprite</a> to draw pixel art!
                The fetch request is called every second using the setInterval function in javascript.
