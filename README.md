# optimization-project
Udacity FEND Opt. Project
# Project Explanation 
We've been provided with a website that contains a lot of performance issues and the goal is to:
1. index.html achieves a PageSpeed score of at least 90 for Mobile and Desktop.
1. Optimizations made to views/js/main.js make views/pizza.html render with a consistent frame-rate at 60fps when scrolling.
1. Time to resize pizzas is less than 5 ms using the pizza size slider on the views/pizza.html page. Resize time is shown in the browser developer tools.
# Repository Structure
There's two directories in the repo: 
* src 
which contains the source code with comments and clear indentations. (readable)
* dist
which contains the production code and minified versions of html/css/js files.

Basically they're are only different in two files index.html and js/perfmatters.js where minifying has been done. The rest are the same.

# Set up 
To run the website you have two options:
Either to run it locally and that's by cloning the repo and then hosting it locally with the help of python and ngrok.
Helpful guide can be found
[here](https://github.com/udacity/frontend-nanodegree-mobile-portfolio)
or you can view it directly from here with the help of github pages:
[optimization-project](https://mousa96.github.io/optimization-project/dist/)
# Approach
1. Achieving 90 or more score on index.html
* Made the google analytics script async
* Used a web font loader to load the font async
* Added a media="print" attribute to the print.css link
* Optimized and compressed images (profilepic and pizzeria) with the help of pagespeed suggestions
* Inlined style.css
* Minified perfmatters.js 
* Minified index.html  
Page speed Score:  
* Mobile: 99
* Desktop: 96
### Sources and tools used: 
* [Pagespeed](https://developers.google.com/speed/pagespeed/insights/)
* [Web Font Loader](https://github.com/typekit/webfontloader)
* [HTML minifier](https://www.willpeavy.com/minifier/)


2. Pizzeria slider optimization and consistent 60 fps animations
* Replaced queryselectors with getElementById/ClassName
* Calculated the number of pizzas dynamically based on screen size
* Moved every forced repeated declartion outside of loops
* Implemented RequestAnimationFrame to improve animation
* There is comments throughout the main.js explaining each changes.
### Source and tools used:
* mentioned in the comments
