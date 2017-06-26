# Earthquakes Monitor

This is a very simple single-page visualisation of the recent earthquakes around the world, using HTML and JavaScript.

It was developped to experiment with the Leafleft map library and playing around with reading JSON data from a web service.

More information [here](http://www.justahype.net/projects/earthquakes.html).

A live demo is available at: [http://www.justahype.net/earthquakes](http://www.justahype.net/projects/earthquakes.html)

This code is under the [MIT License](License.txt). Each of the dependencies - libraries, data or other - belong to their respective authors and are subject to their respective LICENSES.

# Libraries used

- [JQuery 2.2.0](https://github.com/jquery/jquery)
- [JQuery UI 1.11.4 with theme "Smoothness"](https://github.com/jquery/jquery-ui)
- [Leaflet 0.0.7](https://github.com/Leaflet/Leaflet)
- [jQRangeSlider](http://ghusse.github.io/jQRangeSlider) (JQuery plugin)
- [SlideReveal](http://nnattawat.github.io/slideReveal/)
- [Font Awesome](https://github.com/FortAwesome/Font-Awesome)

# Data used

The application relies on the open data about recent earthquakes made available by the USGS ([https://earthquake.usgs.gov/](https://earthquake.usgs.gov/]))

The data usage and redistribution is subject to the license provided on the [USGS website](https://earthquake.usgs.gov/]).

# Screen captures

![Screenshot of the application](/screenshots/earthquakes.jpg "Screenshot of the application")
*Screenshot of the application*

The "Infos & Settings" pane can be unfolded from the top-right corner of the page. From there, is is possible to change the filters for the earthquakes displayed on the map, using the magnitude and the time frame period to display (maximum one month ago).

![Settings panel](/screenshots/settings.jpg "Settings panel")
*Settings panel*

There is also an option to show on the map the boundaries of the tectonic plates by checking a box in the Settings.

![Boundaries displayed](/screenshots/boundaries.jpg "Boundaries displayed")
*Boundaries displayed*