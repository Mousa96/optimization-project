# optimization-project
Udacity FEND Opt. Project
# Project Explanation 
We're provided with a website that contains a lot of performance issue and the goal is to:
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
Helpful guide can be found here
[Link](https://github.com/udacity/frontend-nanodegree-mobile-portfolio)
or you can run view it directly from here with the help of github pages:
[Link](https://mousa96.github.io/optimization-project/dist/)
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
Mobile:
Desktop: 
img
**Sources and tools used: **
* [Pagespeed] (https://developers.google.com/speed/pagespeed/insights/)
* [Web Font Loader] (https://github.com/typekit/webfontloader)

