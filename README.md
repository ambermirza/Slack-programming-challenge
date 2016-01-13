# photoalbum
* Uses the Flickr API to create a web page where a user can search "london" and the page will show a grid of photo thumbnails pulled from Flickr.
* When a thumbnail is clicked, the photo will be displayed in a lightbox view, with the ability to move to the next / previous photos and display the caption.
* When at the last picture (in lightbox view), clicking the next button will start from the top

# bugs
* If search two different items, the newest "response" will be added to the bottom
  * Need to reset allpics[] each time 
