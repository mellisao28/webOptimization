## Website Performance Optimization portfolio project is to optimize this online portfolio for speed! 

How to run 
-----------------------
Click on index.html or visit my GitHub page (https://rawgit.com/mellisao28/webOptimization/master/index.html) and enjoy the app.

Changes to original version
----------------------------------
index.html
- only load print.css when media="print"
- Inline and minified CSS
- Use async for javascript
- Compressed images


pizza.html
- Add viewport tag in header
- Inline and minified CSS
- Use various image sizes 
- Minified javascript and use async

main.js
- change changePizzaSizes to only loop the part to update width
- change looping for pizza generator to get the first 2 pizzas outside of the loop
- change updatePosition to use cachedScroll and phaseCount

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