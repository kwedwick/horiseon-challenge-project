# Code Refactor Starter Code
1) Started with opening the website to see what is displayed inforrectly / not pathing correctly compared to the example

Visual Errors:
1) Navigation list not properly sized
2) Search Engine Optimization doesn't nav link
3) Text and boxes don't wrap when shrunk

Looking at HTML:
1) Div soup!
2) Change en-US
3) Header is a div class instead of an element
4) Title only says "website"

5) no "id=S-E-O" for the nav link to SEO
6) Img and h2/p codes are not in the correct orders for SEO/ORM/SMM 
7) Image link for Cost Management incorrect
8) Classes and id's for "section content" are the same. ID and Class shouldn't be the same
9) Class float-right left should be in CSS not inline
10) Alt=""'s added for all images


10) Div classes for right box don't match the respecitve content
11) Looks like a lot of CSS classes for benefit section and all sections. Will simplify in CSS 

12) Footer is classified as a div

Anything not noted here I noted in the html doc in <!-- -->

Fixing Following HTML:
Notes in HTML

CSS:
-Redo for header as not a class
-Redo "Hero" section of div in CSS
-Changed div to nav in sections
-Need to combine a lot of sections. Removing classes for all under <section class="content"> to apply stlyes to all and then sub define for positioning
-Same as above for Benefits. Combine all CSS to fall under section
-Fix to path correctly to footer instead of a footer class
-CSS for all of the sections weren't grouped correctly - fixed.
Added media queries to try them out. Only one scale issue with iPad.