# Visual Studio Code Github Repository Setup
Step-by-step instructions for setting up a repository in Visual Studio Code environment.

## Instructions
1. Create a new repository on Github.
2. Copy the link of your Github repository.

   ![image](https://github.com/sidneyshafer/vs-code-github-setup/assets/66838571/e3b593a7-9fba-4a65-a86b-4d318693bbb6)

4. Open terminal in Visual Studio Code and write the following commands:
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
