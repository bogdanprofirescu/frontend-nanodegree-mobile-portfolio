**STEPS FOR RUNNING THE APPLICATION**

For running the application please click the following link:
https://bogdanprofirescu.github.io/frontend-nanodegree-mobile-portfolio/index

For seeing the each portfolio page click on each of the corresponding links.

**OPTIMIZATIONS**

Optimizations on the index.html for Critical Rendering Path:

- inlined the content of  style.css
- added the "media=print" attribute for the print.css
- removed the fonts request
- optimized all images (sizes and quality)
- made the analytics script "async"

Optimizations made on views/js/main.js:

- reduced the no of pizzas from 200 to 20, when DOMContentLoaded
-in updatePosition(), changed the selector document.querySelectorAll in document.getElementsByClassName
- changed function changePizzaSizes, so that document.querySelectorAll is used only once, optimized the for loop so that it changes only the newwidth


Optimizations made on pizza.html:

-optimized images for web(size & quality)
