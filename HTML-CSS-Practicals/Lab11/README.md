# Assignment 11: Units And Css Variables

## Experiment Title
Units And Css Variables.

## Aim
This experiment covers the following objectives: To compare fixed and relative CSS units by creating two boxes and larger paragraph text; To define three CSS variables in :root and use them for page colour, padding and heading colour; To define primary colour, accent colour, heading size and spacing tokens and apply them to page styles.

## Software / Tools Required
Computer, Git (for Assignments 1–2), a text editor (such as VS Code) and a modern web browser.

## Theory
- px is a fixed CSS length unit; % is relative to a containing block; rem is relative to the root element font size.
- CSS custom properties are declared with a `--` prefix and accessed using var(). Defining variables in :root makes them available throughout the document.
- Design tokens are reusable values stored as custom properties. They make design updates consistent and reduce repeated literal values.

## Task 1: Use px, percentage and rem units

### Algorithm / Procedure
Create a 200px by 40px box, a 50% by 40px box and a paragraph with 1.5rem font size.

### Input
View at a browser window wide enough to show the 50% box.

### Output
The first box is 200px wide; the second occupies half its container; paragraph text is larger.

### Result
The px, percentage and rem units were demonstrated.

## Task 2: Define and use CSS custom properties

### Algorithm / Procedure
Declare --main-color, --accent-color and --page-padding in :root; apply them to body and h1.

### Input
Open variables.html.

### Output
The heading uses accent red; body text uses the main navy colour and page padding is 20px.

### Result
CSS variables were declared and reused with var().

## Task 3: Create reusable design tokens in CSS

### Algorithm / Procedure
Create tokens.css with the four specified variables; use them for body colour and padding and h1 colour and size.

### Input
Link tokens.css from an HTML page in the same folder.

### Output
The linked page uses navy body text, 16px padding, red h1 text and a 2rem heading size.

### Result
Reusable CSS design tokens were defined and applied.
