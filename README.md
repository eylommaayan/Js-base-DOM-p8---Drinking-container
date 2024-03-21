Selecting Elements: It selects elements from the DOM using document.querySelectorAll() and document.getElementById() and assigns them to variables.

Event Listener: It attaches a click event listener to each small cup element (cup-small). When a small cup is clicked, it calls the highlightCups() function, passing the index of the clicked cup.

Highlighting Cups: The highlightCups() function updates the visual representation of the cups based on the index of the clicked cup. It adds the class full to cups up to the clicked cup and removes the class from cups after it.

Updating Big Cup: The updateBigCup() function calculates and updates the state of the big cup based on the filled small cups. It adjusts the height and visibility of the percentage bar and the remaining liters indicator.

Calculations: It calculates the percentage of filled cups, adjusts the height of the percentage bar, and updates the remaining liters indicator based on the filled cups.
