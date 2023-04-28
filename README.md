

images

original creation
logo-bw.png 

credited images
hero-bg1 from unsplash (Wojciech Then) optimized in tinyPNG with 69% smaller size

jula.jpg/leon.jpg/johan.jpg from pixbay popimized in tinyPNG with 73%
smaller size

colorpalette chosen with online picker from hero-bg1
$floral-white: rgba(247, 244, 235, 1);
$french-gray: rgba(200, 211, 217, 1);
$delft-blue: rgba(35, 56, 91, 1);
$paynes-gray: rgba(95, 114, 140, 1);
$delft-blue-2: rgba(34, 49, 77, 1);


credit
responsive hero 600px navbar inspired by w3schools responsive navbar

KNOWN BUGS
Testimonials section
when zeroing margin-left in t-image class for the responsive 500px section to center all pictures above text, ”Leons” picture runs away.
Temporary fix: Keep a margin of 1vw and its not noticable.

Bug found:
Found the bug through chrome dev tools. The reason was a float: right from earlier on ”Johan” (the reversed part of testimonials)
Actual fix:
Float can be removed because in responsive section they all use flex as is new convention, though float is still being taught in the course, and this project reflects that.

ABOUT THE SECTIONS - Words from the coder

HERO

REASONS TO JOIN US
This is probably the simplest part of the website where im trying a way of using grid rows to convey the "reasons to join" simply and also easily make it responsive.
I think it works well but maybe there is an even easier way of using grids, flexbox would have worked well here too.

TIMELINE
This was an attempt to use what I know about grids to make a very simple minimalist timeline, it ended up being a lot more code than I had planned. I am very pleased with the result so it was worth it.
Kept in style with the speechboxes from the previous section but styled more informative and less comic-like.


TO DO

change size of bgimage becaouse of newsletter size