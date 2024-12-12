# CSS Specificity Bug: Unexpected Styling from Conflicting Selectors

This repository demonstrates a common yet subtle CSS bug related to selector specificity.  The bug highlights a situation where a more specific selector doesn't override a less specific one due to the order of CSS rules and how specificity is handled. 

## Bug Description:

A seemingly correct and more specific CSS selector fails to apply its styles because of a conflict with a less specific selector. The issue is rooted in CSS specificity rules and the cascading order of style sheets.

## How to Reproduce:
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the `.box` element inside `#container` doesn't have the expected styles. The `#container .box` selector seems to be ignored.

## Solution:
The solution involves understanding and adjusting for CSS specificity.  Refer to `bugSolution.css` for a corrected version.