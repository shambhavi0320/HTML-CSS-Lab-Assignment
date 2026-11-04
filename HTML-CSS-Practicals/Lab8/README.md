# Assignment 8: Sign-Up Forms And Choices

## Experiment Title
Sign-Up Forms And Choices.

## Aim
This experiment covers the following objectives: To create a POST form with labelled full-name, email and password fields; To create two gender radio choices and a course dropdown with BCA and B.Tech; To make full-name and email fields mandatory and provide a placeholder for the name field.

## Software / Tools Required
Computer, Git (for Assignments 1–2), a text editor (such as VS Code) and a modern web browser.

## Theory
- The form element groups controls. Labels improve usability and accessibility when their for attribute matches the input id. Password inputs conceal typed characters.
- Radio inputs with the same name form a mutually exclusive group. The select element creates a dropdown and option defines each choice.
- The required attribute triggers browser validation before form submission. A placeholder gives a short input hint but does not replace a label.

## Task 1: Create a labelled sign-up form

### Algorithm / Procedure
Create form with method post and action thanks.html; add three associated labels and inputs.

### Input
Enter a name, valid email and password in the form. Submission target is thanks.html as specified; that file is not required.

### Output
Three labelled fields appear. Password characters are masked while typing.

### Result
A sign-up form with correctly associated labels and input types was created.

## Task 2: Add radio buttons and a course dropdown

### Algorithm / Procedure
Create a gender fieldset with two radio inputs sharing a name; add a select with two options.

### Input
Select one gender option and choose a course from the dropdown.

### Output
Only one radio option can be selected at a time; the dropdown contains BCA and B.Tech.

### Result
Radio choices and a course dropdown were implemented successfully.

## Task 3: Use required fields and a placeholder

### Algorithm / Procedure
Create full-name and email inputs; add required to both; add a name placeholder and submit button.

### Input
Try submitting the form with one or both fields empty, then enter valid values.

### Output
The browser displays a validation prompt when a required field is empty.

### Result
Required validation and a placeholder were added to the sign-up form.
