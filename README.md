# Git Command

## Initialization

Use this command at the first time. and don't forget to add  ```.gitignore``` file if your project needs it

1. Add git to your project
```
git init
```
2. Add all your working directory / all changes to git 
```
git add .
```
3. Commit after you create changes / new file or directory
```
git commit -am "your commit mmessage"
```
4. Add your new remote and give name to it. i use origin as name of remote here
```
git remote add origin your_url_remote
```
6. Push all your commit to your remote
```
git push --set-upstream origin master
```
7. Set your new remote as default remote
```
git branch --set-upstream-to origin/master
```
## Common

Most used git command

1. Cheking changes of your project
```
git status
```
2. Add all your changes / new directory / file
```
git add .
```
3. Commit your changes
```
git commit -am "your commit message"
```
4. Pull your team changes to your project
```
git pull
```
5. Push all your commit to your remote
```
git push --set-upstream origin master
```
