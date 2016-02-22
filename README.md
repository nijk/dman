# Approach

This project is an investigation into how DOM manipulation libraries work under the hood. It is not intended to be a 
practical alternative to the many DOM libraries already available.
 
The feature set is very basic and focuses on three areas:

1. DOM selection via `document.querySelectorAll()`
2. Node creation via `document.createElement()`,  `Node.appendChild()`, `Element.setAttribute()` & `Element.classList.add()`
3. DOM manipulation via `Node.appendChild()`

For the time being this project relies on `document.querySelectorAll()` to simplify the requirements, this obviously 
will has an impact on the cross-browser support possibilities. 

# Todo

1. Add `package.json` manifest file
2. Add tooling to lint, test & compile a production package 
3. Add a unit testing framework & add coverage for existing functionality
4. Add a richer suite of DOM manipulation methods: `.remove()`, `.clone()`, `.attr()`