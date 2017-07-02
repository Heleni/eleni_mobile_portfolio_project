## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.


### Some useful tips

Documentation for the changes made on the final project

For the index.html file here's what i did: -Minify html, css and js -Compress images -Inline css and set js file to async -Use cache.apcache file to load to cache all files for index.html and subsquent pages

The initial score that pagespeed gave for the index.html file was 72/100 (mobile) and 75/100 (desktop). The final score that pagespeed gave for the index.html file was 94/100 (mobile) and 96/100 (desktop).

Note: I could've set the following code on the .htaccess file, but i didn't know how to fix an error with the fonts located on the inlined css in the index.html file <FilesMatch ".(css|jpg|jpeg|png|js)$"> ExpiresActive on Header set Cache-Control "max-age=604800, public" This way i would've had a 100/100 score on pagespeed website, but only 73/100 for user experience because of the fonts error.

For the pizza exercise (main.js) here's what i did: -Modify 'changePizzaSizes' function so it doesn't take so much to resize the pizzas (Description: line 451;Old code commented: line 456; New code: 463) -Modify 'updatePositions' function so it doesn't take so much to move the background pizzas
  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```
### Getting started
1. Open a browser and visit localhost:8080
2. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.
3.click index.html

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```
