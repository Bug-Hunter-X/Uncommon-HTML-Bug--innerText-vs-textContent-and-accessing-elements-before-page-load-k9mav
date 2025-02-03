# Uncommon HTML Bug: innerText vs textContent and handling element load

This repository demonstrates two uncommon HTML bugs and their solutions:

1. **Incorrect use of `textContent` and `innerText`**:  `textContent` is for plain text, while `innerText` handles richer content like HTML tags.
2. **Accessing elements before they are loaded**: Attempting to manipulate an element before the page has finished loading can lead to errors.  This is handled using an event listener and conditional checks.

The `bug.html` file showcases the incorrect implementation, while `bugSolution.html` provides the corrected version.

This example is particularly helpful for developers learning about the subtle differences in text manipulation in HTML and asynchronous element loading.