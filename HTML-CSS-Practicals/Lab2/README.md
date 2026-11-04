# Assignment 2: Pushing And Cloning A Repository

## Experiment Title
Pushing And Cloning A Repository.

## Aim
This experiment covers the following objectives: To create a bare repository and add it as the origin remote; To transfer local commits to the configured remote repository; To create a working copy by cloning the remote repository and inspect its history.

## Software / Tools Required
Computer, Git (for Assignments 1–2), a text editor (such as VS Code) and a modern web browser.

## Theory
- A bare repository stores Git data without a working directory and is commonly used as a remote. `git remote -v` lists remote URLs for fetch and push.
- `git push` sends local commits to a remote branch. The branch may be named main or master depending on repository configuration.
- `git clone` copies a repository, including its commit history, into a new directory.

## Task 1: Create and inspect a bare remote repository

### Algorithm / Procedure
From html-lab, create ../html-remote as a bare repository; add origin; inspect remotes.

### Input
Existing local repository html-lab.

### Output
The output lists origin with the same path for fetch and push.

### Result
A bare remote repository was created and connected as origin.

## Task 2: Push commits to the remote repository

### Algorithm / Procedure
Check the current branch; push it to origin using the matching branch name.

### Input
Commits in the local repository and a configured origin remote.

### Output
Git confirms that the local branch was pushed to the corresponding remote branch.

### Result
The local commit history was pushed successfully to origin.

## Task 3: Clone the remote repository

### Algorithm / Procedure
Move to the parent directory; clone html-remote into html-copy; enter it; view the log.

### Input
The local bare repository html-remote containing pushed commits.

### Output
The cloned repository shows the same commits as the source repository.

### Result
The remote repository was cloned and its commit history was verified.
