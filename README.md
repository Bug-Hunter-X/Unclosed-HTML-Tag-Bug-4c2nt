# Unclosed HTML Tag Bug

This repository demonstrates a common HTML error: an unclosed tag.  Unclosed tags can lead to unexpected layout problems, and make the HTML difficult to read and maintain.

## Bug Description
The `bug.html` file contains an unclosed `<b>` tag. This will cause the rest of the text in the paragraph to be rendered as bold, and will create validation errors. 

## Solution
The `bugSolution.html` file demonstrates the correct way to use HTML tags, with all tags being properly closed.  This fixes the rendering problems and ensures that the HTML is valid.

## How to reproduce
1. Open `bug.html` in your browser.
2. Observe the unexpected bold formatting.
3. Open `bugSolution.html` in your browser. 
4. Observe the correct formatting. 