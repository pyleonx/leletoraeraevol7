HOW TO ADD YOUR PHOTOS
======================

Put your image files inside this "images" folder and use these exact filenames:

01-cover.jpg      - opening page photo
02-memory.jpg     - page 2, left memory
03-memory.jpg     - page 2, right memory
04-us.jpg         - apology letter photo 1
05-us.jpg         - apology letter photo 2
06-us.jpg         - apology letter photo 3
07-favourite.jpg  - final "yes" page favourite photo

You can replace the filenames in the HTML if you want.
Example:

<img src="images/myphoto.jpg" alt="Us together" />

Supported browser formats include .jpg, .jpeg, .png, .webp and .gif.
If you use a PNG instead, either rename it to the filename expected by the HTML,
or update the src= path in that page.

IMPORTANT:
Keep the entire apology_website folder together. Do not move the HTML files away
from the images folder, otherwise the relative image paths will stop working.
