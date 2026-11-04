# Assignment 12: Box Model, Cards And Scrolling

## Experiment Title
Box Model, Cards And Scrolling.

## Aim
This experiment covers the following objectives: To compare two boxes with equal width, padding and border but different box-sizing values; To create a card with background colour, 2px border, 12px rounded corners and 16px padding; To create a fixed-height box with automatic overflow scrolling and five paragraphs.

## Software / Tools Required
Computer, Git (for Assignments 1–2), a text editor (such as VS Code) and a modern web browser.

## Theory
- In content-box, declared width applies to content and padding/border are added outside. In border-box, declared width includes content, padding and border.
- A card is a common UI component used to group related content. CSS background, border, border-radius and padding control its appearance and spacing.
- The overflow property controls content that exceeds an element’s box. `overflow: auto` adds scrollbars when content requires them.

## Task 1: Compare content-box and border-box

### Algorithm / Procedure
Create two div boxes with width 200px, padding 20px and border 5px; apply different box-sizing values.

### Input
Open box-model.html and compare the outer widths.

### Output
The content-box element has a larger outer width than the border-box element.

### Result
The effect of the two box-sizing values was demonstrated.

## Task 2: Style a card component

### Algorithm / Procedure
Create a div with class card; place an h3 and paragraph inside; apply the specified styles.

### Input
Open card.html.

### Output
A coloured card appears with a 2px border, rounded corners and internal spacing.

### Result
A styled card component was created successfully.

## Task 3: Create a scrollable content box

### Algorithm / Procedure
Create a 120px-high div; set overflow:auto; add five paragraph lines.

### Input
Open scroll.html and scroll inside the content box.

### Output
The fixed-height box displays a scrollbar because the five lines exceed its height.

### Result
A scrollable box was created using overflow:auto.
