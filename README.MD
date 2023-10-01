# What is Git?
Git is a version control system used for tracking changes in computer files or in software code.

# What is Github?
Github is a open source program that uses git commands to store our program files.
It stores folders that are known as repository. Repository can be private or public.

# Git Configuration
After installing the git and github into the local machine. Need to configure the git to upload all the changes
into the github account in the selected repo.

git config --global user.name "User name"
git config --global user.email "github user email"
git config --list


# Git Commands

1. Clone:- To clone any repo to the local machine. 
   Command:- git clone <git url>

2. Status:- To know the status of the code.
   Command:- git status

3. Add:- adds new or changed files in your working directory to the Git staging area.
   Command:- git add <file name>
   For all files at the same time use :- git add . 

4. Commint:- It is the record of change.
   Command:- git commit -m "some message"

5. Push:- Upload local repo content to remote repo.
   Command:- git push origin main

6. Branch:- To check on which branch we are.
   Command:- git branch



# Git Commands to make a local folder to git repo

1. Init:- To initialize a local folder for a git repo.
   Command:- git init

2. Remote:- To make a local folder to a git repo.
   Command:- git remote add origin <repo link>

3. Verify:- To verify that a git repo is created for our local folder.
   Command:- git remote -v




