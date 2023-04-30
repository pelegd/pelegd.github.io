---
title: Git Cheet Sheet
date: 2023-04-30 07:50
categories: [Git,Cheetsheet]
tags: [guide,cheetsheet,git] #should always be lower case
---
###  Setting up Git
git config --global user.name "Your Name" : Set your Git username
git config --global user.email "youremail@example.com" : Set your Git email address
git config --list : List all Git configuration settings

### Creating a new repository
git init : Create a new local repository
git clone [url]: Clone an existing repository from a remote source

### Adding and committing changes
git add [file] : Add changes to the staging area
git add . : Add all changes to the staging area
git commit -m "Commit message" : Commit changes to the local repository with a message

### Working with branches
git branch: List all branches
git branch [branch-name]: Create a new branch
git checkout [branch-name]: Switch to a specific branch
git merge [branch-name] : Merge changes from a specific branch into the current branch
git push origin [branch-name] : Push changes to a remote repository

### Working with remote repositories
git remote add origin [url] : Add a remote repository
git pull : Fetch and merge changes from a remote repository
git push : Push changes to a remote repository
git remote -v : List all remote repositories

###  Other helpful commands
git status: Show the status of your repository
git log : Show the commit history of your repository
git diff [file]: Show the changes made to a specific file.