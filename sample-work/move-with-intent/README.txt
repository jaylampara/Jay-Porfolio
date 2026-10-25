# Move With Intent — sample works

Every folder inside THIS folder shows up automatically as a TAB in the
"Move With Intent" modal. Rename, add or delete any folder and the tabs
follow (rename with a number prefix to control the tab order, e.g.
"5 - Client reels").

Each tab folder accepts a free mix of any of these:

  PHOTOS      1.png, 2.jpg, 3.webp, 4.gif   (PNG/JPG/JPEG/WEBP/GIF/AVIF)
  VIDEOS      1.mp4, 2.mov, 3.webm          (vertical/horizontal auto-detected)
  LINK FILES  1.txt                          (see below)

Filenames are visible in the directory listing, so any number works and no
exact count is required. Files are ordered by the number in their name.

## Link files (1.txt …)

A .txt file holds ONE link on its first non-comment line:

  https://www.youtube.com/watch?v=KpcGPX6TqJQ | My reel
  https://www.instagram.com/reel/xxxx/        | Vertical spot
  https://drive.google.com/file/d/FILE_ID/view

Accepted: YouTube & Vimeo (auto-embed, muted loop, ♪ to unmute), direct
photo/video URLs, Google Drive & Dropbox share links, X/Twitter posts,
Streamable & Dailymotion & Loom & TikTok clips, Instagram & Facebook
videos, and any page that serves a photo. Vertical and horizontal
previews auto-detect like local files. Lines starting with # are ignored.

## Google Drive rules

- The file MUST be shared as "Anyone with the link" (Viewer) — otherwise
  nothing can fetch or play it. Unshared files show "Sign in" inside the
  Drive player instead.
- A DRIVE VIDEO plays inside Drive's own player (with its own sound
  control) and its tile grabs the video's real shape (vertical/square/
  horizontal) from its thumbnail.
- A DRIVE PHOTO becomes a normal photo tile automatically — if a photo
  ends up in a Drive player anyway, add the word photo to the label:
  "https://drive.google.com/file/d/FILE_ID/view | Vertical photo"
