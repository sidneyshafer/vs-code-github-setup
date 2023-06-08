# Visual Studio Code Github Repository Setup
This repo contains instructions for setting up a repository in Visual Studio Code environment.

## Instructions
1. Create a new repository on Github.
2. Copy the link of your Github repository.
3. Open terminal in Visual Studio Code and write the following commands:
```
git init
git add .
git commit -m 'Initial Commit'
git remote add origin [your github repo link]
git branch -M main
git push -u origin main
```
To Commit Code - *after repository has been connected to github:*
```
git add .
git commit -m 'Code Commit'
git push
```
