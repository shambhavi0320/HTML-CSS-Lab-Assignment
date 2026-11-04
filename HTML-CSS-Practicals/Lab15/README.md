# Assignment 15: Responsive Pages With Media Queries

## Experiment Title
Responsive Pages With Media Queries.

## Aim
This experiment covers the following objectives: To stack two cards on small screens and place them side by side at 600px and above; To make an image shrink to fit its container while maintaining its aspect ratio; To set base text sizes in rem and enlarge the h1 at viewport widths of 600px and above.

## Software / Tools Required
Computer, Git (for Assignments 1–2), a text editor (such as VS Code) and a modern web browser.

## Theory
- A mobile-first design starts with styles for small screens and uses min-width media queries to enhance layouts for wider screens. The viewport meta tag helps pages scale correctly on mobile devices.
- `max-width:100%` prevents an image from exceeding its parent width. `height:auto` preserves the image aspect ratio as width changes.
- The rem unit is relative to the root font size. Media queries apply CSS only when their conditions match the viewport or device.

## Task 1: Create a mobile-first two-card layout

### Algorithm / Procedure
Add viewport meta; define stacked cards as base styles; add a min-width:600px media query for two columns.

### Input
View below 600px and then at 600px or wider.

### Output
On narrow screens cards stack; at 600px and above they appear side by side.

### Result
A mobile-first responsive card layout was implemented using a media query.

## Task 2: Make an image responsive

### Algorithm / Procedure
Add a heading and the included sample image; apply max-width:100% and height:auto.

### Input
Open responsive-image.html and resize the browser window.

### Output
The image scales down to fit a narrow container and preserves its proportions.

### Result
A responsive image was created using max-width and automatic height.

## Task 3: Change heading size with a media query

### Algorithm / Procedure
Set body font-size to 1rem and h1 to 1.5rem; add min-width:600px rule setting h1 to 2.5rem.

### Input
View below 600px and then at 600px or wider.

### Output
The heading is 1.5rem on narrow screens and 2.5rem at 600px and above.

### Result
Responsive heading typography was implemented with rem units and a media query.
