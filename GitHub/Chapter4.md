# Chapter 4

## Git branches 

### 1) Creating a new branch

     git branch <branch-name>
     


### 2) To work in a branch, first you need to switch to it. We use git **Checkout** mostly for switching from one branch to another
     
     git checkout <name-of-your-branch>
   
##### **AND**

### 2) There is also a shortcut command that allows you to create and switch to a branch at the same time

     git checkout -b <name-of-your-branch>

##### (-b stands for branch)  
 
     


### 3) This command will create a branch locally. To push the new branch into the remote repository, you need to use the following command

     git push -u <remote> <branch-name>
     


### 4) Viewing branches
     
     git branch or git branch --list



### 5) Deleting a branch:

     git branch -d <branch-name>
     
##### (-d stands for deleting) 



### 6) Git Merge

#### Before merging, you should update your local  branch by following these Command

     git checkout dev
     git fetch

#### Finally, you can merge your feature branch into dev:

     git merge <branch-name>






     
  
     
