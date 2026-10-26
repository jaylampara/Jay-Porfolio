# Client reviews

Each review is one numbered .txt file, plus a picture with the same number:

  reviews/1.txt      review text + star rating
  reviews/1.jpg      small square picture (jpg / png / webp / gif / avif / svg)

Copy this format into 1.txt:

  stars: 5
  message: Jay turned a messy lead flow into a system the team actually uses every day.

Only "stars" and "message" are required.

  stars      1, 2, 3, 4 or 5   (or paste up to five ★ characters)
  message    the review text; it can continue on more lines

The picture is matched by the number in the filename: 1.txt pairs with
1.jpg (or 1.png, 1.webp, 1.gif, 1.avif, 1.svg). It is cropped to a square.

If the picture has a different name or extension, point to it from the txt:

  image: client-name.jpg

The strip reads this folder automatically on localhost and GitHub Pages.
Add as many numbered reviews as you like; they are ordered by the number.
On GitHub Pages, wait for the deployment to finish, then open the page in a
new tab (the folder list is cached for five minutes).
This README is ignored.
