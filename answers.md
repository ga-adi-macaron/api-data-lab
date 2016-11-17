##### Task #1: Find the api call that allows you to search for all images of "cats".

API Call: https://api.flickr.com/services/rest/?api_key=7db48ffe022ec0ad6006b0498c82dfb9&method=flickr.photos.getRecent&tag=cat

##### Task #2: Find the api call that allows you to search for all images from "Charlotte, North Carolina.

API Call: 
1. Use to get the place_id.
https://api.flickr.com/services/rest/?api_key=7db48ffe022ec0ad6006b0498c82dfb9&method=flickr.places.find&query="Charlotte, North Carolina"

2. Search by place_id
https://api.flickr.com/services/rest/?api_key=7db48ffe022ec0ad6006b0498c82dfb9&method=flickr.photos.search&place_id=KtHrHAVTUb1F.npO


##### Task #3: Get all of the comments for any photo.

API Call: https://api.flickr.com/services/rest/?api_key=7db48ffe022ec0ad6006b0498c82dfb9&method=flickr.photos.comments.getList&photo_id=2756752672

##### Task #4: Search for a list of all the photos in your current latitude and longitude.
API Call: https://api.flickr.com/services/rest/?api_key=7db48ffe022ec0ad6006b0498c82dfb9&method=flickr.photos.getRecent&lat=40.5959&lon=-73.9418&radius=5&radius_units=km
