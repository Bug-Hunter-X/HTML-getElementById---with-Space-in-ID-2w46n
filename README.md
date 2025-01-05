# HTML getElementById() Issue with Space in ID

This repository demonstrates a common yet easily overlooked HTML error related to using `getElementById()` with an element ID containing a space.  The issue arises because `getElementById()` is case-sensitive and fails to select elements with spaces in their IDs.  The `bug.html` file showcases the incorrect implementation, while `bugSolution.html` provides the corrected version.

## How to reproduce the bug

1. Open `bug.html` in a web browser.
2. Observe that the text within the div element is not replaced as expected.

## Solution

The solution involves either using camel case or underscores in the ID or the use of querySelector, which is more robust.

Refer to `bugSolution.html` for a working example.