# CSS Specificity Bug: Unexpected Color Inheritance

This repository demonstrates a subtle bug related to CSS specificity. The issue arises when trying to style paragraphs nested within divs, leading to unexpected color inheritance in some browsers.

## Bug Description
The provided CSS code intends to style paragraphs differently depending on their context. Paragraphs directly within a div should be blue, while other paragraphs should be red. However, due to specificity rules, this doesn't always work as expected in all browsers.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe the unexpected color of the nested paragraph.  

## Solution
The solution involves increasing the specificity of the second rule to ensure it takes precedence.  See `bugSolution.css` for a fix using more specific selectors.