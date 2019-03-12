# VirtualTourist

An iOS App uses 
- URLSessions to interact with a public restful Flickr API.
- Create a user interface that intuitively communicates network activity and download progress.
- Store media on the device file system Use Core Data for local persistence of an object structure

###### App functionality - coredata model to maintain user state , added pins and corresponding downloaded images . App supports delete ,update , empty functionality in coredata model.

Home screen Persist 
- last location , zoom level of map.

Map screen Persist
- downloaded images corresponding to last Pin selected otherwise download fresh set of images from flickr using lat long.


###### Home page
<img src="Homescreen.PNG" width="250" height = "400">


###### Home page Zoom
<img src="Homescreen1.PNG" width="250" height = "400">


###### Map View Page While Fetching
<img src="mapscreen1.PNG" width="250" height = "400">

###### Map View Page While Fetching2
<img src="mapscreen2.PNG" width="250" height = "400">

###### Map View Page After Downloaded
<img src="mapscreen3.PNG" width="250" height = "400">
