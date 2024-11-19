# Etch a Sketch

This is a simple Etch a Sketch project built with HTML, CSS, and JavaScript. It allows users to create a customizable grid and draw on it with random colors as they hover over the individual cells.

## Features

- **Dynamic Grid Size**: Users can set the size of the grid (1-100).
- **Random Color Generation**: Each time you hover over a pixel, its background color will change to a random RGB color.
- **Progressive Color Change**: Each subsequent hover on a pixel results in a more intense color change.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/etch-a-sketch.git
2. Open `index.html` in a web browser to start using the Etch a Sketch.

## Usage

- Click on the **"Set Grid"** button to choose the grid size (from 1 to 100).
- Move your mouse over the grid to color the individual pixels.
- The background color of each pixel changes to a random color when you hover over it.
  
## How It Works

### HTML

- The `index.html` contains the structure of the page, including:
  - A title and header (`<h1>Etch a Sketch</h1>`)
  - A button to trigger the grid size input
  - A container (`#grid-container`) that holds the grid elements

### CSS

- The styling ensures that the grid is centered and that each pixel is visible and clickable.
- The grid has a border around it, and each pixel has a small border to make it distinct.

### JavaScript

- **Grid Creation**: The `addGrid()` function creates the grid dynamically based on the input size.
- **Pixel Interaction**: When the user hovers over any grid cell, the background color changes to a random color using `changeToRandomColor()`.
- **Grid Size Adjustments**: The user can prompt for a new grid size using the `Set Grid` button, which updates the grid and resets the pixels.

## Customization

You can adjust the following to personalize the Etch a Sketch:
- **Grid Size**: Modify the `gridSize` variable in the JavaScript file to change the default size.
- **Color Change Speed**: The `interaction` variable controls the intensity of the color change. Increasing its value will make the color change more rapidly.
