# Assignment 13: Flexbox Layouts

## Experiment Title
Flexbox Layouts.

## Aim
This experiment covers the following objectives: To arrange four navigation links horizontally using display:flex; To place three pricing cards in one row and center them using justify-content and align-items; To display four stationery product cards that wrap onto additional rows on narrow screens.

## Software / Tools Required
Computer, Git (for Assignments 1–2), a text editor (such as VS Code) and a modern web browser.

## Theory
- Flexbox is a one-dimensional layout model. `display:flex` creates a flex container whose direct children become flex items.
- `justify-content` aligns flex items along the main axis; `align-items` aligns them along the cross axis.
- The flex-wrap property controls whether flex items remain on one line or wrap onto multiple lines when space is limited.

## Task 1: Create a horizontal navigation bar with Flexbox

### Algorithm / Procedure
Create a nav element with four links; use display:flex, dark background and white link text.

### Input
Open nav-flex.html.

### Output
A dark horizontal bar displays four white links side by side.

### Result
A horizontal navigation bar was arranged using Flexbox.

## Task 2: Center three cards using Flexbox

### Algorithm / Procedure
Create a row container and three cards with the specified names and prices; apply Flexbox centering.

### Input
Open centred-cards.html.

### Output
Starter, Standard and Premium cards appear centered in one row when sufficient width is available.

### Result
Three cards were centered using Flexbox alignment properties.

## Task 3: Create a wrapping Flexbox card row

### Algorithm / Procedure
Create four cards with the specified product names and prices; set display:flex and flex-wrap:wrap.

### Input
Resize the browser window to a narrow width to observe wrapping.

### Output
Cards occupy one or more rows depending on available width.

### Result
A responsive wrapping card layout was created with flex-wrap.
