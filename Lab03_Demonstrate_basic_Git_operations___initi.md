# Lab 03: Demonstrate basic Git operations — initialize, add, commit, and push code to a remote GitHub repository.

## Objective
 To Demonstrate basic Git operations — initialize, add, commit, and push code to a remote GitHub repository.

## Tools / Technologies
Git and Github

## Prerequisites
Git bash

## Steps / Commands
Step 1: Create a Folder
mkdir gitDemo
cd gitDemo

Step 2: Initialize a Local Git Repository
git init

Step 3: Create a Sample File
echo "Hello, MyGit" > read.txt

Step 4: Add File(s) to the Staging Area
git add read.txt
git add .

Step 5: Commit the Changes
git commit -m "Initial commit with readme file"

Step 6: Create a Remote Repository on GitHub
Create a new repository in Github and name it git_demo

Step 7: Connect Local Repo to GitHub
git remote add origin https://github.com/Akhil-004062006/git-demo.git
git remote -v  
# Verify remote connection

Step 8: Push Code to GitHub
git branch -M main
git push -u origin main

## Expected Output / Result
 Expected outputs
 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 232 bytes | 232.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Akhil-004062006/git-demo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.


## Deliverables (what to push)
- `Labs/Lab03_<ShortTitle>.md` (this file, completed)
- Any additional scripts, Dockerfiles, manifests, or screenshots placed in a folder named `Lab03_files/`

## Notes / Tips
- Add any helpful hints or troubleshooting tips here.

 

