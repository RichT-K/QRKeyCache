# QRKeyCache
QRKeyCache is a GEO location treasure hunt like, GEO Caching, in which biodegradable images containing a QRCode are placed at specific locations.  
A player accesses the site/app to find an image.
With with GEO nav enabled the closest 10 or so non-located images are shown on the map.
Proximity to an image increases the resolution of the image's location.
When the player finds the image they scan the QR Code taking them to the page which records their find, also updating the map.

There are time limits on each game which should be reflected on the page 
and accounted for when an inactive game image code is scanned. When enough players indicate an active image is unreadable 
it may be replaced with a new image or deactived from the game. 

A goal is to incorporate local business to sponsor prizes for the players who complete the game with the most finds 
in the shortest accumulated time.

Games will have themes related to the participating business.
Non-business related games, public and private, may be created for other groups or organizations.

The list of images in each game will continuously update to show the number of players that have found the image,
the shortest time each image was found, the time remaining ... along with other data specific only to the player.

The game will utilize OSM(Open Street Map) first, Google Map and Bing Map as secondary options.

Game admins or designated "placers" affix and scan images to record the locations, after images are in place the game admin activiates the game
at which time the game becomes visible to players accessing the site or a private game url. 
