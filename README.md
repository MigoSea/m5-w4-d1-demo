# Module 5 - Week 4 Day 1 Demo: DOM & DOM APIs

This repository contains the completed in-class exercises for **Module 5 Week 4 Day 1** (**WEB 403 / 603 Full Stack Web Development**, Westcliff University).

## Demos Overview

### 1. In-Class Demo #1: DOM Node Creation (`demo1.html`)
- Dynamically creates an `<h1>` element using `document.createElement("h1")`.
- Creates a text node containing `"Big Head!"` using `document.createTextNode("Big Head!")`.
- Appends the text node to the heading node (`heading.appendChild(heading_text)`).
- Appends the heading to the document body (`document.body.appendChild(heading)`).

### 2. In-Class Demo #2: Dynamic Body Attributes (`demo2.html`)
- Implements `setBodyAttr(attr, value)` with error handling to dynamically update `document.body` attributes.
- Connects dropdown `<select>` `onChange` handlers for:
  - **`text`**: Switch between `black` and `red`.
  - **`bgColor`**: Switch between `white` and `gray` (`lightgrey`).
  - **`link`**: Switch between `blue` and `green` for sample link colors.

### 3. In-Class Demo #3: React Click Events & Element IDs (`demo3/`)
- Built with React 17, ReactDOM, and Babel CDN.
- Implements `handleClick(event)` method inside `OnClickElements` class component.
- Triggers alert displaying the clicked element's ID (`alert(\`hey! you clicked: \${event.target.id}\`)`).
- Applied to various elements including `<div>`, `<span>`, `<button>`, and `<a>` styled links and button blocks.

---

## How to Run Locally

1. Open `demo1.html` in any modern web browser to view the generated DOM heading.
2. Open `demo2.html` in any web browser to test dynamic text, background, and link color changes.
3. Open `demo3/index.html` in a web browser (or via a local live server / extension) to interact with the React elements and view the click alerts.
