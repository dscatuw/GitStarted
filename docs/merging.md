# Part 3 - Merging

## Fundamentals

`git checkout [<branch>]`

Use this command to switch to the branch you would like to merge to.


`git merge [<branch>]`

This command allows your to merge into the current branch. This command will leave the branch you are merging from completely unaffected, but, by default, result in a new commit in the current branch (and of course, you can override it by adding the flag `--no-commit`). 






---

## Additional

// TODO merging conflict?

### Notes


1. Although you may think of it as merging two branches together for now, the command `git merge [<branch>]` actually merges two commits.