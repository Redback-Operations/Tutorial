# Ben's Git and GitHub Tutorial
Git Tutorial

This is a Tutorial for project for app in python

to install requirements type `pip install -r requirements.txt`

Author:
@Ben-AI-cybersec

# Morgaine's branching example
Go to your terminal or your vs code terminal - the commands are the same
- Clone the repository
- Create a branch
- Make changes
- Commit changes
- Push changes

## Clone the repository

git clone https://github.com/Redback-Operations/Tutorial.git


## Enter the repository - change your terminals focused directory to where you made the clone. This will depend on where you chose to store the clone.

cd ~/User/Documents/GitHub/githubusername/Tutorial

## Make sure you're on main
git checkout main

## Get the latest changes
git pull origin main

## Create and switch to your branch (after the -b you decide what you want the branch to be called, I suggest using your name and feature you’re adding/developing.)
git checkout -b update-readme-example

# Edit README.md (or whichever file you are working on) and save!

git status
git add README.md
git commit -m "Add GitHub clinic workflow instructions"

git push -u origin mb-readme-update

