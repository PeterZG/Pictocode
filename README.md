# PicToCode

## Introduction

PicToCode is a project focused on creating web pages that replicate specific design images using HTML and CSS. The tasks aim to reinforce skills in layout design, responsiveness, and visual consistency. Each task requires the implementation of a page that closely follows the provided design specifications.

## Project Structure

The project contains three main tasks, each with its own folder:

- **task1/**: Implements a static, fixed-size page layout.
  - `index.html`: Main HTML structure for Task 1.
  - `index.css`: CSS for layout and styling for Task 1.
  - `assets/`: Contains images (`img1.png`, `img2.png`, `img3.png`) and other resources used in Task 1.
  - `page.png`: Reference image provided as a design guideline for Task 1.

- **task2/**: Develops a responsive layout that adapts to two specific screen sizes.
  - `index.html`: Main HTML structure for Task 2.
  - `index.css`: CSS for layout and styling for Task 2.
  - `assets/`: Contains icons (`icon1.png`, `icon2.png`, `icon3.png`, `icon4.png`, `icon5.png`) used in the design for Task 2.
  - `page_big.png` and `page_small.png`: Reference images for different screen sizes in Task 2.

- **task3/**: Expands on responsiveness with more complex layout adjustments across wider screen ranges.
  - `index.html`: Main HTML structure for Task 3.
  - `index.css`: CSS for layout and styling for Task 3.
  - `assets/`: Contains icons and SVGs (`svg.svg`, `svg2.svg`) used for various pricing features in Task 3.
  - `page_big.png` and `page_small.png`: Reference images for large and small screen sizes in Task 3.

## Task Details

### Task 1: Static, Fixed-Size Page

Replicate a static layout as shown in `page.png`:

- **Layout**: Three sections in a grid, each containing an image, a title, description, and call-to-action link.
- **Location**: `task1/index.html`, `task1/index.css`
- **Style**: Grid layout with fixed width (1981px) and height (844px).

### Task 2: Responsive Layout with Two Sizes

Create a responsive layout that adjusts between `page_big.png` (1040 x 577) and `page_small.png` (501 x 592):

- **Layout**: Row-to-column layout changes based on screen size.
- **Location**: `task2/index.html`, `task2/index.css`
- **Responsive Behavior**: Uses media queries to adjust layout direction and element spacing.

### Task 3: Responsive Layout with Wide Adaptability

Develop a responsive layout that adjusts for larger screens between `page_big.png` (1595 x 895) and `page_small.png` (673 x 3034):

- **Layout**: Four pricing tiers displayed in flexible rows or columns.
- **Location**: `task3/index.html`, `task3/index.css`
- **Responsive Behavior**: More extensive use of media queries for wider adaptability, adjusting font sizes, button layouts, and visibility of elements.

## Running the Project

To view each task, open the corresponding `index.html` file in a web browser. Resize the browser window to observe responsive behaviors in Task 2 and Task 3.
