# Useful-Git-Commands


#Setting up git
$ git config --global user.name "User Name"
$ git config --global user.email "email"

#Initializing a repository in an existing directory
$ git init
$ git add <file>
$ git add README
$ git commit -m 'Initial project version'

#Checking the status of your files
$ git status

#Staging files
Adding a file
$ git add filename
Adding all files
$ git add -A
Adding all files changes in a directory
$ git add .


#create branches
$ git checkout <branch name>  //To Change the branch
$ git branch <branch name>   //Create a branch in git



#Fetching and checking out remote branches
This will fetch all the remote branches for you.
$ git fetch origin

# With the remote branches in hand, you now need to check out the branch you are interested in, giving you a local working copy:
$ git checkout -b test origin/test

# Deleting a remote branch
$ git branch -rd origin/branchname
$ git push origin --delete branchname  or  $ git push origin:branchname


#Merging branch to trunk/master
First checkout trunk/master
$ git checkout trunk/master

Now merge branch to trunk/master
$ git merge branchname

To cancel a merge
$ git merge --abort


#Updating a local repository with changes from a Github repository
$ git pull origin master



#Git remote
Show where 'origin' is pointing to and also tracked branches
$ git remote 
$ git remote add origin
$ git remote add origin url

Show where 'origin' is pointing to
$ git remote -v

Change the 'origin' remote's URL
$ git remote set-url origin 

# Add a new 'origin'
Usually use to 'rebase' from forks
$ git remote add [NAME] 

#Push project/files to existing git repo
$ git pull <url>
$ git add .
$ git commit -m "message goes here"
$ git remote add origin <url>  //not required
$ git push -u origin master   //not required
