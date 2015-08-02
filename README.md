## Website Performance Optimization portfolio project 
The goal of this project is to optimize an online portfolio for speed! 

How to run 
-----------------------
Click on index.html or visit my GitHub page (https://rawgit.com/mellisao28/webOptimization/master/index.html) to see preview but please note that not all functionality may work properly in the preview.

Changes from original version
----------------------------------
index.html
- only loaded print.css when media="print"
- Inlined and minified CSS
- Used async for javascript
- Compressed images


pizza.html
- Added viewport tag in header
- Inlined and minified CSS
- Used various image sizes 
- Minified javascript and use async

main.js
- changed changePizzaSizes to only loop the part to update width
- changed looping for pizza generator to get the first 2 pizzas outside of the loop
- changed updatePosition to use cachedScroll and phaseCount
- changed the number of sliding pizzas to 35

How to use PageSpeed Insights
----------------------------------
1. Run a local server
$> cd /path/to/your-project-folder
$> python -m SimpleHTTPServer 8080
Open a browser and visit localhost:8080

2. Use ngrok too make your local server accessible remotely.

In a new command prompt window:
$> cd /path/to/your-project-folder
$> ngrok http 8080
  
3. Use PageSpeed Insights
Copy the public URL ngrok gives you and try running it through PageSpeed Insights (https://developers.google.com/speed/pagespeed/insights)
