# Git Commands

> **.gitignore**   Add list of  file/folder to ignore while committing file in git . Example :  /node_module


```
git config --global user.name 'name'   //To change the git user name
git config --global user.email 'email@gmail.com'  //To change git email 
``` 

```
git init  //Initialize Local Git Repository
git add <File>   //Add field to index
git add .   //Add all the file/folder
git status  //Check status fo working tree
git commit -m "messages goes here"  //Commit changes  
git push  //Push to remote repository
```
```
git pull  //Pull latest from remote repository
git clone <url>   //Clone repository
```

```
git stage  //Stage all changes
git rm --cached <file name>  //To unStage file
```
```
esc :wq   //To come out from edit mode.
```


```
git checkout <branch name>  //To Change the branch
git branch <branch name>   //Create a branch in git
git merge <branch name>   //Merge branch to current branch
```

```
git remote  //List all the remote repository
git remote add origin https://github.com/ksunilssah/HTML.git   //Add branch to Local
git push -u origin master
```
```
git remote add origin https://github.com/ksunilssah/HTML.git   //Push existing branch to github
git push -u origin master
```


## Push  project/files to existing git repo
```
git pull <url>
git add .
git commit -m "message goes here"
git remote add origin <url>  //not required
git push -u origin master   //not required
```
