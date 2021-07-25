# Chapter 5


#### 1) Git Revert

#### Sometimes we need to undo the changes that we've made
#### A safer way that we can undo our commits is by using "git revert". To see our commit history, first we need to use
     
     git log -- onelin
     
#### Then we just need to specify the hash code next to our commit that we would like to undo:
     
     git revert <last-commit-code>

### press shift + q to exit


# Advantages of Revert


### The advantage of using git revert is that it doesn't touch the commit history. This means that you can still see all of the commits in your history, even the reverted ones. 

### Another safety measure here is that everything happens in our local system unless we push them to the remote repo. That's why git revert is safer to use and is the preferred way to undo our commits.
