# Uncommon HTML Bug: Inconsistent Div Clearing and Hiding

This repository demonstrates an uncommon bug related to clearing the innerHTML of a div and setting its display style to "none" in HTML and JavaScript.

The bug showcases inconsistent behavior across different browsers when attempting to completely remove content from a div by setting innerHTML to an empty string and simultaneously setting display to "none".  This might lead to unexpected visual results or layout issues.

**Bug Description:**
The initial HTML contains a div with some text. A button triggers a JavaScript function that clears the div's content (innerHTML = "") and hides it (style.display = "none"). While this appears to work in most browsers, subtle differences might occur.

**Solution:**
The solution file clarifies how to consistently clear and hide divs across browsers, addressing the potential inconsistencies.

