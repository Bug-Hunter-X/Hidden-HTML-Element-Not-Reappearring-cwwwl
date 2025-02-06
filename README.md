# Hidden HTML Element Bug

This repository demonstrates a common yet easily overlooked error in HTML and JavaScript: an element is hidden using JavaScript, but there's no way to make it reappear. The `myFunction` hides the div, but the user cannot restore visibility. 

## Bug Description:

The `bug.html` file contains a div element that is hidden by a button click.  The problem is that the JavaScript only provides functionality to hide the element, not to show it again.  The solution is provided in `bugSolution.html`.