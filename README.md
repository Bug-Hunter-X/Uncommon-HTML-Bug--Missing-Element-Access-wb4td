# Uncommon HTML Bug: Missing Element Access

This repository demonstrates a subtle bug in HTML that can occur when attempting to access a DOM element that may not exist.  The bug is demonstrated in `bug.html` and a solution is presented in `bugSolution.html`.

The bug arises from directly accessing a DOM element (using `getElementById`) without first checking if the element actually exists.  If the element isn't present, this will result in a JavaScript error.

The solution involves adding a check to ensure the element exists before attempting to modify its properties.

This is an uncommon error because it requires a specific condition (a missing element) which might not be immediately apparent from inspecting the code.