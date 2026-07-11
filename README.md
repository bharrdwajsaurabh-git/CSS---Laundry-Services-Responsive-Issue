# CSS Selectors Demonstration

## Overview
This project is a simple demonstration of how different **CSS Selectors** work to target and style specific HTML elements. It includes examples of element, class, ID, descendant, and structural pseudo-class selectors.

## Files Included
* `index.html`: The main HTML structure containing various text elements, unordered lists, and ordered lists.
* `style.css`: The stylesheet that applies specific rules to the HTML using different targeting methods.

## CSS Concepts Covered

### 1. Element Selectors
Targets HTML tags directly.
* `body`: Sets the background color to coral.
* `p`, `ul`: Sets the default text color to white.

### 2. Class Selectors (`.`)
Targets elements with a specific class attribute.
* `.head`: Applies dark blue text color to all headings (`h1`, `h2`, `h4`) sharing this class.

### 3. ID Selectors (`#`)
Targets a unique element on the page.
* `#bglime`: Gives the `h2` heading a specific green background color.
* `#para`: Styles a specific paragraph with a distinct green text color.

### 4. Combinators / Child Selectors (`>`)
Targets elements that are direct children of other elements.
* `#bglime>span`: Targets the `span` directly inside the element with the ID `bglime`, making it red.
* `p>span`: Targets `span` elements directly inside paragraphs, making the text black and larger.

### 5. Structural Pseudo-classes (`:`)
Targets elements based on their position within a parent element.
* `ul li:first-child a`: Targets the anchor tag in the very first list item of an unordered list (yellow background).
* `ul li:last-child a`: Targets the anchor tag in the last list item of an unordered list (blue background).
* `ol li:nth-child(2)`: Targets exactly the 2nd item in the ordered list (blue text).
* `ol li:nth-child(3)`: Targets exactly the 3rd item in the ordered list (red text).

## How to Use
1. Ensure both `index.html` and `style.css` are saved in the same directory.
2. Open `index.html` in any modern web browser to see the CSS styles applied to the HTML structure in action.
