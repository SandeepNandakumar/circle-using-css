# Centered Red Circle

This project demonstrates how to create a perfectly centered red circle using HTML and CSS with Flexbox.

## Features

- A red circle with a border
- Centered both vertically and horizontally using Flexbox
- Responsive to viewport height

## How to Use

1. Open `index.html` in any modern web browser.
2. You will see a red circle centered on the page.

## Code Snippet

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.circle {
  width: 200px;
  height: 200px;
  background-color: red;
  border-radius: 50%;
  border: 2px solid red;
}
