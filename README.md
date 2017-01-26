# Virtual Graffiti

Originally an Android augmented reality app where users could take a photo, draw on it, and leave the drawing in 3d space where other users could view. 

Currently the app allows the user to take a photo, draw on it, and save it to a marker which is then placed on the map for other users to see. The latitude and longitude is taken from the photo data and used to make the marker on the map, making it very precise. Markers are shown in a 3 mile radius from the user's current location, which is updated every 5 seconds. Upon clicking a marker, the drawing is superimposed on the photo. 

Augmented reality was the goal and still is possible. We are storing the photo and drawing separately for future use of just the drawing to put into 3d space. Photo data from the phone's camera has spacial data we would need to position the drawing in 3d space. 

## Dependencies and instructions:
Rails 4, Heroku, Apache Cordova, Ionic, Cordova plugins: whitelist, camera, geolocation. 

* npm install -g cordova ionic
* ionic start Virtual-Graffiti blank --v2--ts
* npm install -g cordova
* cordova plugin add cordova-plugin-whitelist
* cordova plugin add cordova-plugin-camera
* cordova plugin add cordova-plugin-geolocation

## Contributors:
- [@busster](https://github.com/busster)
- [@corbin1987](https://github.com/corbin1987)

## Screenshots:
https://cloud.githubusercontent.com/assets/19857615/22320696/34d9d330-e354-11e6-9ae2-f0973bca776d.png
