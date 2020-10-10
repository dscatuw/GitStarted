# Part 2 - Branching
Allows you to do cool stuff when you are working on multiple features of one project or working with others
# Fundamentals
```git checkout another_branch_name``` 
git checkout can actually be used without the given branch name, checkingout without specification would set HEAD to be the current branch. 


**NOTE:** changes would be discarded.


```git checkout -b new_branch_name```


Adding the -b flag creates a new branch with the given name, similar to what ```git branch``` does. 


```git branch```



```git switch```


```git restore```
Introduced by Git 2.25.0, used instead of git reset from this version onward.


```git reset --hard [<commit>]```
Hard mode discarded all changes after ```<commit>```, this also resets the index. 


```git reset --soft```
This would leave all changed files as "changes to be committed" and same as ```git status``` would put.


```git merge``` 


# Additional
Below are a bunch of commands that might become handy when you want to keep track of the branches and commits.

```git branch --all``` ```git branch``` is a powerful command that can create, check, or delete branches. Use ```git branch``` with the ```--all``` flag to list all local branches and remote branches you chose to track.

```git branch -d <branchname>``` Use this command to delete any branch. **NOTE:** Git will only let you do this when the branch it tries to delete is merged into the upstream branch (usually the master branch, if the term "upstream branch" sounds unfamiliar).

```git log``` Use this command to check commit history. Although simple as ```git log``` would do the job, I strongly recommend you to look up and experiment with some possible options it offers to let you customize what, how, and how much you want to see.
## Notes
1. Example use ``` git restore --staged <file>..." to unstage)```, if a file was named README.md from README, unstaging would revert the name back to README.
