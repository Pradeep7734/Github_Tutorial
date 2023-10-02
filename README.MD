# What is Git?
Git is a version control system used for tracking changes in computer files or in software code.

# What is Github?
Github is a open source program that uses git commands to store our program files.
<br>
It stores folders that are known as repository. Repository can be private or public.

# Git Configuration
After installing the git and github into the local machine. Need to configure the git to upload all the changes
<br>
into the github account in the selected repo.

git config --global user.name "User name"
<br>
git config --global user.email "github user email"
<br>
git config --list


# Common Git Commands

1. Clone:- To clone any repo to the local machine.
<br>
   Command:- git clone <git url>

2. Status:- To know the status of the code.
<br>
   Command:- git status

3. Add:- adds new or changed files in your working directory to the Git staging area.
<br>
   Command:- git add <file name>
   <br>
   For all files at the same time use :- git add . 

4. Commit:- It is the record of change.
<br>
   Command:- git commit -m "some message"

5. Push:- Upload local repo content to remote repo.
<br>
   Command:- git push origin main

6. Branch:- To check on which branch we are.
<br>
   Command:- git branch

7. Rename Branch:- To change the branch name.
<br>
   Command:- git branch -M <branch name>



# Git Commands to make a local folder to git repo

1. Init:- To initialize a local folder for a git repo.
<br>
   Command:- git init

2. Remote:- To make a local folder to a git repo.
<br>
   Command:- git remote add origin <repo link>

3. Verify:- To verify that a git repo is created for our local folder.
<br>
   Command:- git remote -v



# Git Branch Commands

1. Branch:- To check on which branch we are.
<br>
   Command:- git branch

2. Rename Branch:- To change the branch name.
<br>
   Command:- git branch -M <branch name>

3. Create Branch:- To create a new branch.
<br>
   Command:- git checkout -b <new branch name>

4. Change Branch:- To shift from one branch to another.
<br>
   Command:- git checkout <branch name>

5. Delete Branch:- To delete a branch. But you should be on another branch.
<br>
   Command:- git branch -d <branch name>



# Git Merge Command

There are two ways:

1. Difference:- To check the difference in data in between the branches.
<br>
   Command: git diff <branch name>

2. Merge:- To merge out changes with the specific branch
<br>
   Command: git merge <branch name>

Second way to raise the PR:

1. PR (PULL REQUEST):- It lets you tell others about changes you've pushed to a branch in a repository on GitHub.


# Git Pull Command

1. Pull:- It is used to fetch and download content from a remote repo and immediately update the local repo
<br>
                  to match that content.
                  <br>
   Command:- git pull origin main



# Git Merge Conflict Command

1. Merge Conflict:- An event that takes place when Git is unable to automatically resolve differences in code
<br>
                    between two commits when you have same change in the file.
                    <br>
   Command:- There is no command for this.


# Git Reset Changes

1. After add:- Used to reset the changes after the git add command
<br>
   Command:- git reset <file name>
   <br>
   Command to reset all:- git reset

2. After commit:- Used to reset the changes after the git commit command
<br>
   Command for one commit:- git reset HEAD~1
   <br>
   Command for many commit:- git reset <- commit hash ->
   <br>
   Command for many commit:- git reset --hard <- commit hash ->




