annotate
========


What
----

Put a text and EXIF caption on images, directly on the viewable image. Control the size, position, and orientation.

How
---

ruby annotate.rb -t "title/text of image" -i input\_file.jpg -o output\_file.jpg

Bottom right vertical placement of the text:
ruby annotate.rb -t "title/text of image" -i input\_file.jpg -o output\_file.jpg -d bottom-right-vertical

-d takes 3 words joined by dashes. The first position is top or bottom, the next is left or right, and the last is the orientation: horizontal or vertical. Examples:

top-left-horizontal
top-left-vertical
top-right-horizontal
top-right-vertical
bottom-left-horizontal
bottom-left-vertical
bottom-right-horizontal
bottom-right-vertical


Why
---

ImageMagick command line syntax is dense, impenetrable, and very powerful. I
wrote a shellscript at first, and then I wanted to do more comlpicated things
from command-line options, so I did a Ruby script.


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
