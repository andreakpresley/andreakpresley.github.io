## Website Performance Optimization portfolio project

To view this application, go to https://andreakpresley.github.io

To run locally, download the project and open index.html

### How to test
1. PageSpeed: Go to https://developers.google.com/speed/pagespeed/insights/ and enter the URL given above
2. Fps: Record the timeline while scrolling and then view results
3. Time for pizzas to resize: View console while resizing

### Optimizations made

#### index.html
1. Inlined the stylesheet (style.css)
2. Added the media attribute and set it to 'print' for the print.css file
3. Added font face attribute to style sheet
4. Removed some style attributes and moved those to the style inlined as mentioned above

#### main.js
1. Changed all "querySelector" calls to use "getElementBy.."
2. Removed determineDx() method
3. Refactored changePizzaSizes() to use percentage values for width
4. Removed unnecessary calculations in the for loop in changePizzaSizes()
5. Created a variable for length for for loops
6. Created a variable for the inner scroll calcuation in updatePositions()
7. Added requestAnimationFrame() calls when calling updatePositions()
8. Moved movingPizzas element variable to outside of the for loop
