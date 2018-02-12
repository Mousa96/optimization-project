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
