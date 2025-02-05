# CSS :has() Pseudo-class Specificity Bug

This repository demonstrates an uncommon bug related to the CSS `:has()` pseudo-class and selector specificity. The bug occurs when trying to style a parent element based on a child element's class, leading to unexpected behavior in some cases.

## Bug Description
The intention is to style list items only when their direct child anchor element has the `active` class. However, due to how CSS handles selector specificity, the styling may not apply as expected depending on other styles or the document's structure.

## Solution
The solution involves adjusting the selector specificity to ensure the desired styling is applied correctly. This might involve adding an extra class or making sure the selector is more specific to override other potentially conflicting styles.

## Files
- `bug.css`: The CSS code that demonstrates the bug.
- `bugSolution.css`: CSS code that provides the solution to this bug.