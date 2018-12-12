# Map - What They Drop on New Year's Eve
This is a map of objects that are dropped on New Year's Eve.
I made it based on [this Wikipedia page](https://en.wikipedia.org/wiki/List_of_objects_dropped_on_New_Year%27s_Eve)
There is a static map (nye.jpeg) and an interactive version (newyre.html)

The static map was made mostly using QGIS, the interactive map is via Leaflet using
a basemap from CARTO. **Beware** - Sometimes the interactive map does not load all points on the first try. If only a few appear, refresh the page.

### Notes about the data on the map

The Wikipedia page that was the source for this map is subject to changes at any time and may have already changed since this map was created.  Some of the items listed on that page were either one time events or have been discontinued. These were not included on the map.  There are two locations outside of the United States (Bermuda and Canada) that were not included but may be added at a later time. There is an obvious Pennsylvania bias in the results as much of this came from an article in [Penn Live](https://www.pennlive.com/entertainment/index.ssf/2016/12/new_years_eve_2016_strange_qui.html) - this is also where I first saw some of these and got the idea for the map. See map notes below for how this was handled cartographically.

### Mapping Notes

The locations are from a canned US cities dataset and are not accurate when zoomed in too far. The locations reference cities or towns and are not meant to represent the locations of the drop events. In some cases they may be several miles away. The Key West locations were moved slightly so both objects would be readable. There are (at this time, December, 2018) no objects listed in Alaska or Hawaii. This allowed me to zoom the map in and not need the inset maps commonly seen for these states. Instead, I was able to use those spaces for Pennsylvania, which has such dense data that it needed two separate insets, one just focused on Harrisburg. A couple of other areas, particularly northern Georgia are also very dense. The interactive version was created for this problem.


