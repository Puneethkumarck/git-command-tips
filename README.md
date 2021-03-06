# git-command-tips
This project contains git command tips

### Create a new repository on the command line
 ```
touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin  https://github.com/Puneethkumarck/spring-cloud-microservice-playground (eg remote git repo url)
git push -u origin master
```
 
### Push an existing repository from the command line
 
 ```
git remote add origin  https://github.com/Puneethkumarck/spring-cloud-microservice-playground (eg remotegit repo url)
git push -u origin master
```

### Issues 

fatal: refusing to merge unrelated histories

```
git pull origin master --allow-unrelated-histories
```

### To remove git history from github

```
Checkout

git checkout --orphan latest_branch

Add all the files

git add -A

Commit the changes

git commit -am "commit message"

Delete the branch

git branch -D master

Rename the current branch to master

git branch -m master

Finally, force update your repository

git push -f origin master
```
### specify author while commiting

```
git commit --author 'username <example.com>' -am "commit message"
```

### adding files to stage for commit

```
git add -A stages All

git add . stages new and modified, without deleted

git add -u stages modified and deleted, without new
```

### Undo Commit and untrack the file
```
undo the latest commit
git reset --soft HEAD^1

remove file from staging area
git rm --cached <file-name>

```
### Using multiple git accounts
## local config
 + git config user.name "**************"
 
 + git config user.email "*************" 



