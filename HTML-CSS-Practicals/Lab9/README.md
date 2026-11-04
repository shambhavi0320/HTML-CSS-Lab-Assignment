# Assignment 9: Tables With Headers And Footers

## Experiment Title
Tables With Headers And Footers.

## Aim
This experiment covers the following objectives: To create a captioned table with a header and three student records; To create a marks table for Asha and Rohan and calculate the subject averages in tfoot; To improve table accessibility using scope="col" and scope="row".

## Software / Tools Required
Computer, Git (for Assignments 1–2), a text editor (such as VS Code) and a modern web browser.

## Theory
- The table element represents tabular data. Caption describes the table; thead groups headings and tbody groups data rows.
- The tfoot element groups summary rows. Average is calculated as sum of values divided by the number of values. Maths average=(78+64)/2=71; Science average=(85+70)/2=77.5.
- The scope attribute indicates whether a header applies to a row or column, helping assistive technologies interpret table relationships.

## Task 1: Create a marks table with header and body

### Algorithm / Procedure
Create a caption; add Name, Maths and Science headings; add the three specified rows.

### Input
Use the supplied three student records.

### Output
A table appears with a caption, three column headings and three student rows.

### Result
The marks table was created with thead and tbody.

## Task 2: Add a table footer with class averages

### Algorithm / Procedure
Use the same caption and headings; add Asha and Rohan; add a footer row containing the calculated averages.

### Input
Marks: Asha (78, 85), Rohan (64, 70).

### Output
The footer displays Maths average 71 and Science average 77.5.

### Result
The table footer and correct class averages were added.

## Task 3: Add scope attributes to table headers

### Algorithm / Procedure
Add scope="col" to each column header and scope="row" to each student-name header cell.

### Input
Use the Asha and Rohan records; inspect th elements in browser developer tools if needed.

### Output
The table looks like a standard marks table; header cells carry the requested scope attributes.

### Result
Scope attributes were added to improve table accessibility.
