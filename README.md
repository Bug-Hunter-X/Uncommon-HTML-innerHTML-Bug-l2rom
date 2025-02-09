# Uncommon HTML innerHTML Bug

This repository demonstrates an uncommon bug related to modifying the innerHTML property of an HTML element. The bug occurs when attempting to append new HTML content to the existing innerHTML string directly using string concatenation. This approach fails to correctly update the DOM, resulting in the new content not being displayed.

The `bug.html` file contains the erroneous code. The `bugSolution.html` file shows the correct approach to adding new HTML content using DOM manipulation.