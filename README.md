# GitHub

## How to Upload files in the main directory 
### Initialize the Git Repo
* git init
### Add the files to Git index
* git add -A or git add .
The git add command is used to tell git which files to include in a commit, and the -A (or --all) argument means “include all”.
### Commit Added Files
* git commit -m 'Added my project'
### Add a new remote origin
* git remote add origin git@github.com:shubhamnsut/my-new-project.git
### Push to GitHub
*git push -u -f origin main

In one go for a new upload 
  * git init
  * git add -A
  * git commit -m 'Added my project'
  * git remote add origin git@github.com:sammy/my-new-project.git
  * git push -u -f origin main

For making changes in already created file 

* Clone the repository locally
* Make the changes to the local version
* Commit the changes locally
* Push the changes back up to the GitHub repository
