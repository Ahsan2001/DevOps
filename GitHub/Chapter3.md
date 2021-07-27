# Chapter 3

## Uploading Code to github


#### 1) To add a Single File:

     git add <file-name>
     
     
#### 2) To add Everything at Once:

     git add -A  (OR)  git add .
     
#### 3) Git Commit 

##### Git commit is like setting a checkpoint in the development process which you can go back to later if needed.
##### We also need to write a short message to explain what we have developed or changed in the source code
##### *Important:* Git commit saves your changes only locally.

     git commit -m "your message"
     
     
#### 4) Git Push

##### After committing your changes, the next thing you want to do is send your changes to the remote server. Git push uploads your commits to the remote repository.

     git push <remote> <branch-name>

##### However, if your branch is newly created, then you also need to upload the branch with the following command:

     git push --set-upstream <remote> <name-of-your-branch>
     git push -u origin <branch_name>
     
##### *Important:* Git push only uploads changes that are committed.



#### 4) Git pull

##### The git pull command is used to get updates from the remote repo. This command is a combination of git fetch and git merge which means that, when we use git pull, it gets ##### the updates from remote repository (git fetch) and immediately applies the latest changes in your local (git merge).

     git pull <remote>
     
     
     

    
