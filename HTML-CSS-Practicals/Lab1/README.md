# Assignment 1: Starting A Git Repository

## Experiment Title
Starting A Git Repository.

## Aim
This experiment covers the following objectives: To create a lab folder, initialize Git, and configure repository-specific identity; To create an HTML file, inspect its status, stage it and save it in Git history; To update the HTML page, create a second commit and view the concise history.

## Software / Tools Required
Computer, Git (for Assignments 1–2), a text editor (such as VS Code) and a modern web browser.

## Theory
- Git is a distributed version-control system. A repository stores project history. `git config --local` writes identity settings only to the current repository.
- Git tracks changes in the working tree. `git add` stages changes and `git commit` records the staged snapshot.
- A commit represents a saved project state. `git log --oneline` displays abbreviated commit identifiers and messages.

## Task 1: Configure Git for the lab repository

### Algorithm / Procedure
Create `html-lab`; enter it; run `git init`; set local user.name and user.email; display both values.

### Input
A folder name, a display name and an email address.

### Output
Git initializes an empty repository and prints the configured name and email.

### Result
The repository was initialized and local Git identity was configured successfully.

## Task 2: Create and commit the home page

### Algorithm / Procedure
Create index.html; check status; stage the file; commit with the required message.

### Input
The HTML source for index.html.

### Output
The status first shows index.html as untracked; after staging and committing, Git reports one file changed.

### Result
The home page was added to the repository in a commit.

## Task 3: Add a heading and inspect commit history

### Algorithm / Procedure
Add an h2 below the h1; save; stage and commit; display the log.

### Input
Updated index.html containing h1 and h2.

### Output
The log lists two commits, with the newest commit first.

### Result
The second change was committed and the repository history was displayed.
