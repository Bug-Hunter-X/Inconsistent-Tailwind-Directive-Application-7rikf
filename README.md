# Inconsistent Tailwind Directive Application

This repository demonstrates an uncommon bug in Tailwind CSS where directives are not applied consistently across different components.  The problem seems to stem from conflicting CSS rules or incorrect selector precedence, particularly when nesting complex structures or combining directives that affect the same properties.

## Bug
The `bug.html` file shows a simple component where the Tailwind CSS classes are not always applied as expected. The background color and shadow might not be rendered correctly, depending on the HTML structure and other applied directives.

## Solution
The `bugSolution.html` file provides a possible solution. It addresses the issue by examining the specificity of CSS rules, ensuring the correct order of classes, or providing more specific selectors for directives that might be overridden.  The solution might involve using the `!important` flag (with caution) or more precisely targeting elements with specific selectors.  More advanced solutions might include debugging with browser developer tools to investigate conflicting CSS rules.