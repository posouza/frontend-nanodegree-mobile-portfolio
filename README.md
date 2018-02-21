## Udacity Project 4 - Website Optimization

# Instructions

In order to view this project, please doenload all the files and open the 'index.html' file on your favorite browser. To view the pizza website download all of the files and open views/pizza.html in your browser.

# Optimizations to project

1. Moved the document.body request out of for loop in the changePizzaSizes and updatePositions functions. This prevents the browser from having to render the page every time the loop iterates.

2. Cached the needed DOM elements so that the brower isn't querying the DOM every time the for loops are iterated in the updatePositions and changePizzaSizes funcitons.

3. Changed all instances of querySelector to the more efficient getElementById and getElementByClassName depending on whether a class or id is needed.

