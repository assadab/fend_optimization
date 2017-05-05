## Website Performance Optimization Project

This is the 4th project in Udacity's Front End Development Project. To view a live version of the solution, [click here](https://assadab.github.io/fend_optimization/).

### Goals:

- Improve the PageScore of the index.html to at least 90 for mobile and desktop.
- Optimization of Main.js to achieve 60 fps in pizza.html

#### Part 1:  Optimize PageSpeed Insights score for index.html


1. Minify CSS and JS 
2. Inline critical CSS
3. Applied media attribute to appropiate stylesheet
4. Applied async attribute
5. Compressed images with ImageOptim
6. Removed Google Fonts
7. Added cache control meta tags as shown in example:

 ' <meta http-equiv="Cache-control" content="public"> '


 #### Part 2: Optimize Frames per Second in pizza.html

 1. Replaced querySelector with more effective getElementByID
 2. Refactored updatePostions() and resizePizzas();
 3. Used requestAnimationFrame for updatePositions






