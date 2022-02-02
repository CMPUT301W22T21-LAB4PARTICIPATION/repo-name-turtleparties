Lab 4 Participation excercise
This task is for teams. 

1. As a team:

Create an Organization in GitHub and then create a repository (repo name: Team name) under this organization. 
Add your members as collaborators so the whole team will be able to commit their branches.
Create a new Android Studio project (1 project per team) with the same name as the repo name (Team name).
Your android project folder is your local repository and write all the command within this repo/directory.
Use 'git init', 'git add', 'git commit' and 'git push' to push your code to the remote
Use 'git remote add origin' to add the URL of your remote repo to this local repo.
The repository should include .gitignore to not include Android Studio settings files (.idea) and project build folder.
Create an abstract class Shape (java file) with x and y  integer fields (as a team).
Commit the change and push it to GitHub.
2. As a member, on your local machine:

(Do not fork) Clone the repository and create a branch with your name (do not use CCID).
Create a model class (ex. circle, rectangle, star, etc) (new java file) that extends Shape in your own branch.
Commit the change and push the branch to GitHub.
Create a pull request to master in Github.
Ask another member to merge it.
Edit Shape class by adding a color string field. (String color = "blue";) (local your-own branch)
Commit the change. (Don't push it)
3. As a team:

Edit Shape class in the master branch on GitHub by adding a color string field. (String color = "$PUT_YOUR_CHOICE_OF_COLOR";)
Commit the change in GitHub.
4. As a member, on your local machine:

Pull the master branch from GitHub. You should have a conflict. (Origin/master -> local your-own)
Resolve the conflict.
Commit the change.
Push the branch to GitHub.
