# Code Refactor Starter Code

## The Purpose of Project
Started with opening the website to see what is displayed inforrectly / not pathing correctly compared to the example. To get an idea of where to start

Link to live URL project: https://kwedwick.github.io/horiseon-challenge-project/

Link to github repo: https://github.com/kwedwick/horiseon-challenge-project

## Visual Errors:
1. Navigation list not properly sized
2. Search Engine Optimization doesn't nav link
3. Text and boxes don't wrap when shrunk

## Looking at HTML:
1. Div soup!
2. Change en-US
3. Header is a div class instead of an element
4. Title only says "website"
5. no "id=S-E-O" for the nav link to SEO
6. Img and h2/p codes are not in the correct orders for SEO/ORM/SMM 
7. Image link for Cost Management incorrect
8. Classes and id's for "section content" are the same. ID and Class shouldn't be the same
9. Class float-right left should be in CSS not inline
11. Alt=""'s added for all images
12. Div classes for right box don't match the respecitve content
13. Looks like a lot of CSS classes for benefit section and all sections. Will simplify in CSS 
14. Footer is classified as a div
15. Index.html file was in a folder. Was brought out to the front by itself

**Anything not noted here I noted in the html doc in <!- ->**

## Fixing Following HTML:
**Notes in HTML**

## CSS:
1. Redo for header as not a class
2. Redo "Hero" section of div in CSS
3. Changed div to nav in sections
4. Needed to combine a lot of classes there each applying the same effects. Removing classes for all under \section class="content"\ to apply stlyes to all and then sub define for positioning
5. Same as above for Benefits. Combine all CSS to fall under 'section'
6. Fix to path correctly to footer instead of a footer class
7. CSS for all of the sections weren't grouped correctly - fixed.
8. Added media queries to try them out for mobile use to have things scale and format correctly as the window shrinks

## Photo of Completed Project
![Image of Completed Webpage] (./Develop/assets/images/Horiseon-Completed-Webpage.png)
