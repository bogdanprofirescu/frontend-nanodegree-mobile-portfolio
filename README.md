**STEPS FOR RUNNING THE APPLICATION**

For running the application on web please click the following link:
https://bogdanprofirescu.github.io/frontend-nanodegree-mobile-portfolio/index

For running the application locally
  1.  Download(green button on top-right) the application from     https://github.com/bogdanprofirescu/frontend-nanodegree-mobile-portfolio  
  and unzip the file on a local folder.

  2. Please install the free static webserver Fenix, from http://fenixwebserver.com/.  
      Click donwnload from the homepage, and install with all default options.
      Run the Fenix server.
      From the Web Server Menu, click New Server.
      In the new window pick a name for the server and indicate the path to
      the folder where you unzipped the download.
      Hit create button.
      The server will be created in the Fenix window.
      Click the new server name and the default browser will open the app.

For seeing the each portfolio page click on each of the corresponding links.

**OPTIMIZATIONS**

Optimizations on the index.html for Critical Rendering Path:

- inlined the content of  style.css
- added the "media=print" attribute for the print.css
- removed the fonts request
- optimized all images (sizes and quality)
- made the analytics script "async"

Optimizations made on views/js/main.js:

- reduced the no of pizzas from 200 to 48, when DOMContentLoaded
- moved constants out of for loops for the loop creating the pizzas and loop inside the updatePositions()
- in updatePosition(), changed the selector document.querySelectorAll in document.getElementsByClassName
- changed function changePizzaSizes, so that document.querySelectorAll is used only once, optimized the for loop so that it changes only the newwidth


Optimizations made on pizza.html:

-optimized images for web(size & quality)
