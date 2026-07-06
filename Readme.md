# Half & Half Viewport Layout (JavaScript Edition)

A simple, responsive web project that splits the viewport into two equal halves. The left side features scalable text tied to the viewport width, while the right side dynamically renders a vertical list of words using Vanilla JavaScript to parse JSON data and manipulate the DOM.

## Features
* **Perfect 50/50 Split:** Uses CSS Flexbox to ensure the layout takes up exactly 100vw and 100vh with no scrollbars.
* **Viewport Typography:** The "I AM" text on the left uses `vw` (viewport width) units to organically stretch and scale as the browser window resizes.
* **Client-Side Rendering:** Uses Vanilla JavaScript to read a JSON object, create DOM elements (`<p>` tags), and inject them into the right-hand container on page load.
* **Even Spacing:** The injected items are distributed evenly using CSS `justify-content: space-around`.

## File Structure
* `index.html` - Contains the HTML structure, CSS styling, and the inline JavaScript logic.
* `README.md` - Project documentation.

## How to Run Locally

Because this project relies entirely on client-side HTML, CSS, and JavaScript with an inline JSON object, no local web server is required.

1. Clone or download the repository to your local machine.
2. Locate the `index.html` file in your file explorer (Finder on Mac).
3. Double-click `index.html` to open it directly in your default web browser.

*(Alternatively, you can drag and drop the `index.html` file into an open browser window).*