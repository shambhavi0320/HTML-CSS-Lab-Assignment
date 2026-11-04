# Assignment 14: Css Grid Layouts

## Experiment Title
Css Grid Layouts.

## Aim
This experiment covers the following objectives: To arrange six numbered boxes in three equal columns with a 12px gap; To create six gallery boxes using auto-fill and minmax for responsive columns; To create a two-column dashboard with header and footer spanning both columns.

## Software / Tools Required
Computer, Git (for Assignments 1–2), a text editor (such as VS Code) and a modern web browser.

## Theory
- CSS Grid is a two-dimensional layout system. `grid-template-columns` defines column tracks and the fr unit distributes available space proportionally.
- `repeat()` avoids repeating track definitions. `auto-fill` creates as many tracks as fit; `minmax()` sets a minimum and maximum track size.
- The grid-template-areas property names regions of a grid. Each string row describes the placement of named areas.

## Task 1: Create a three-column CSS Grid

### Algorithm / Procedure
Create six div boxes; set display:grid; define three 1fr columns and 12px gap.

### Input
Open grid-first.html.

### Output
Six boxes appear in two rows with three equal columns and 12px gaps.

### Result
A three-column CSS Grid was created successfully.

## Task 2: Create a responsive photo gallery grid

### Algorithm / Procedure
Create a heading and six labelled boxes; use repeat(auto-fill,minmax(150px,1fr)) and 10px gap.

### Input
Resize the browser window to see the number of columns change.

### Output
More boxes fit in each row as the viewport becomes wider; each track remains at least 150px wide.

### Result
A responsive gallery layout was created using CSS Grid functions.

## Task 3: Build a dashboard using named grid areas

### Algorithm / Procedure
Define 200px and 1fr columns; name header, sidebar, main and footer areas; assign each element.

### Input
Open dashboard-areas.html.

### Output
Header spans the top, sidebar is on the left, main is on the right and footer spans the bottom.

### Result
A dashboard layout was built using named grid areas.
