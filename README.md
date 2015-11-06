1. In this project I have changed all querySelectors to appropriate getElementBy...() function.
2. Optimized changePizzaSize() function by removing from the loop variables pizzasDiv, dx, newWidth.
3. In order to calculate the amount of floating pizzas on the screen,  i have used screen.availWidth and screen.availHeight properties.
4. In css file I have added to a .mover class backface property in order to increase the perfomance.
5. Part of .css file was inlined into html in order to increase loading speed.
6. To move the pizzas the original code changed the left style property of the pizza element. This is inefficient because the browser needs to composite, paint, and layout the element every time it moves. I used the translateX style to move the element instead because it only requires compositing (which is cheap).
7. Added the 'print' media query to the print.css file because it is only needed when the user wants to print the page, not at page load.
8. All images were resizied and minified.
9. style.css and main.js were minified.

In order to start the project, open in your browser index.html.
To read about pizza's ingridients press button "Ingridients" on top of the image.
To find out pizzeria's location, push the button "Location"
When scrolling down and up the page will show floating pizzas on the screen.

