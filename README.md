# osm-droid-example
This project is to understand how OSMDroid maps functionality is implemented in an Android Studio Gradle Android project

![alt tag](https://github.com/zurche/osm-droid-example/blob/master/sc.png)

The feature list of this example includes:
- Getting the latest known location of the device and centering the map on it.
- Showing a marker of the latest known location in the map.
- Showing an interactive Compass that points to the geographical north.
- Updating evevry 1 second the Latitude and Longitude of the current selected location and display it on the screen.

Additionally OSM droid stores the maps used in the device under the /mnt/sdcard/osmdroid folder. So we can use the Mobile Atlas Creator (MOBAC) to generate maps and store them in that folder for offline usage.


