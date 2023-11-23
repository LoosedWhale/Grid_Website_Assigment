# Grid Website Assigment

## Seeing how gride works on webstites usin `html` and `css`

<h3 align="left">Languages and Tools:</h3>
<p  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a>   

# Using CSS Grid in HTML and CSS

## Introduction

CSS Grid is a powerful layout system that allows you to design complex web layouts with ease. It provides a two-dimensional grid-based layout system that is ideal for both simple and intricate designs. This guide will help you understand the basics of using CSS Grid in your HTML and CSS to create responsive and flexible layouts.

## Getting Started

To use CSS Grid in your project, follow these steps:

### 1. Create Your HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Your Web Page</title>
</head>
<body>
  <!-- Your content goes here -->
</body>
</html>

```
### 2. Link Your CSS Stylesheet
Create a styles.css file and link it in your HTML file. This is where you'll define your grid layout.

### 3. Define Your CSS Grid
In your styles.css, define the grid container and its items:

```css
body {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* Three equal columns */
  grid-gap: 20px; /* Adjust the gap between grid items */
}

/* Example grid item styling */
.grid-item {
  background-color: #ddd;
  padding: 20px;
  text-align: center;
}
```

## Basic Concepts
### 1. Grid Container Properties
`display: grid;`: Defines the element as a grid container.\
`grid-template-columns`: Specifies the size and number of columns.\
`grid-template-rows`: Specifies the size and number of rows.\
`grid-gap`: Creates space between grid items.
### 2. Grid Item Properties
`grid-column`: Specifies the item's position in the grid columns.\
`grid-row`: Specifies the item's position in the grid rows.\
`grid-area`: Combines `grid-row` and `grid-column` into a single shorthand property.

## Example Usage 
```css
<div class="grid-container">
  <div class="grid-item">Item 1</div>
  <div class="grid-item">Item 2</div>
  <div class="grid-item">Item 3</div>
  <!-- Add more items as needed -->
</div>
```
## Advanced Features
CSS Grid offers advanced features such as grid template areas, auto placement, and responsive design. Explore these features to enhance your layout capabilities.

For more detailed information, refer to the [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/).

Feel free to customize the grid properties based on your project's requirements and design preferences.
