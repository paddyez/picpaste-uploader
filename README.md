picpaste.py - fast image uploading

picpaste.de is a nice website for posting images online. It stores  images up to 2 weeks without access, and it provides a delete link, so  the image can be removed before the chosen time.

With  picpaste.py  you can upload an image real fast: Just  type "picpaste.py /path/to/image.jpg" on the commandline. you will get  the image-link and the deletion-link on standard output, and if xclip is  installed, the image-link is copied to the clipboard.

The MultipartPostHandler library is LGPL licensed, the main script is public domain.
