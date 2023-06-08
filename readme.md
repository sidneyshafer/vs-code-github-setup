# Visual Studio Code Github Repo Setup
This repo contains instructions for setting up a repository in Visual Studio Code environment.

## Instructions
1. Create a new repo on Github.
2. Copy link of Github repo.
3. Open terminal in Visual Studio Code and write the following commands:
```
git init
git add .
git commit -m 'Initial Commit'
git remote add origin [github repo link]
git branch -M main
git push -u origin main
```
To Commit Code (after repo has been connected to github):
```
git add .
git commit -m 'Code Commit'
git push
```
