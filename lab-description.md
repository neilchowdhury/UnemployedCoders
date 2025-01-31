# Lab 4 materials
[slides](https://github.com/cmput301-w25/lab-04/blob/main/Lab4.v2.pdf)


### Sensitive Information and Git
* Git is a version control system which tracks all files, past and current, that you commit to it.
* This means that even if you remove a file or part of a file from your repository, it is still tracked and accessible in the history of your repository.
* As such, if you commit sensitive data, it is very difficult, if not impossible, to remove it.
* Sensitive data includes anything such as ID numbers (like your student ID number), API keys, passwords, etc.
* GitHub as some excellent documentation about best practices for avoiding this, located here.
* There is also information about removing sensitive information from your repository, but this should only be used in an emergency as it can have severe consequences if not done properly.

## Lab 4 participation exercise
This task is for teams.

1. As a team:
    * Create a repository (repo name: Team name) in GitHub.
    * Add your members as collaborators so the whole team will be able to commit to their branches (i.e., for a team of 6, there should be 7 branches including the main branch).
    * Create a new Android Studio project (1 project per team) with the same name as the repo name (Team name).
    * Your android project folder is your local repository and write all the commands within this repo/directory.
    * Use 'git init', 'git add', 'git commit', and 'git push' to push your code to the remote
    * Use 'git remote add origin' to add the URL of your remote repo to this local repo.
    * The repository should include .gitignore to not include Android Studio settings files (.idea) and the project build folder.
    * Before you do anything add the .gitignore file (then commit it) so that you don't push irrelevant files to the repo.
    * Create an abstract class Shape (java file) with x and y integer fields (as a team).
    * Commit the change and push it to GitHub.

2. As a member, on your local machine:
    * (Do not fork) Clone the repository and create a branch with your name (do not use CCID).
    * Create a model class (ex. circle, rectangle, star, etc) (new java file) that extends Shape in your own branch.
    * Commit the change and push the branch to GitHub.
    * Create a pull request to main in Github.
    * Ask another member to merge it.
    * Edit the Shape class by adding a color string field. (String color = "blue";) (local your-own branch)
    * Commit the change. (Don't push it)
    * **As a team:**
      * Edit the Shape class in the main branch on GitHub by adding a color string field. (String color = "$PUT_YOUR_CHOICE_OF_COLOR";)
      * Commit the change in GitHub.
    * **As a member, on your local machine:**
      * Pull the main branch from GitHub. You should have a conflict. (Origin/main -> local your-own)
      * Resolve the conflict.
      * Commit the change.
      * Push the branch to GitHub.

### Submission proceedure:
Create a text file named `lab4-<ccid>.txt`. Include the following. 

`<ccid>` `<github-username>` `<repo-url>` `<branch-name>`

Push the file to your Lab 4 repo.
