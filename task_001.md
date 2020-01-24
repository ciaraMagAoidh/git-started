# Task 1

## Creating your own project on github :octocat:
<br>

### Create a new repository on GitHub for this task
 ![Create Task 1 Repository](images/001-create-repo.PNG)
 ![Alt Text](Create a new repository screen on GitHub for Task 1)

<br>

### Creating a local repository using the terminal (mac) / command prompt (windows)
I am putting all of project folders on the Desktop for this workshop, but you can you whatever folder you like.
(Hit the Enter key to execute each command)
* Change directory to Desktop: ```cd Desktop```
* Make a new directory for this task: ```mkdir git-started-task-1```
* Change directory to the new directory you created in the previous step: ```cd git-started-task-1```
* Initialise this directory as a git repository: ```git init```
* Create a README.md file: ```echo "# Git Started: Task 1" >> README.md
* Add the README.md file. This tells Git that we want this file to be considered for a commit. ```git add README.md```
* Commit the README.md file: ```git commit -m "First commit of the README``` The ```-m``` tells Git that we are including a commit message with this command.
* Add a remote origin to your local repository: ```git remote add origin https://github.com/YOUR_GITHUB_USERNAME/NAME__OF_REPOSITORY_CREATED__EARLIER.git```
* Push to the repository and setup up the origin as the master branch: ```git push -u origin master```

You may be asked to enter your git hub credentials at this point.



git add README.md
git commit -m "first commit"
git push -u origin master


- pushing project to a repo
- commits
- pushing
- pulling
- branching
- merging branches




