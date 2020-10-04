# Part 1 Staging and Committing
## Fundamentals
``` git clone```
First, clone this repository in your preferred way. Either use [GitHub Desktop](https://desktop.github.com/) if you like a to visualize with an interactive window, or paste the URL after this command retrieved from clicking the green button that reads **Code**. No matter which option, you should only clone each repository once.

``` git add```
Followed by the filename(s) you are adding to the repository. Notice this would add any igonore files by default. Need to specify your directory.

``` git commit```
Use this for saving your progress/revisions.
> The new commit is a direct child of HEAD, usually the tip of the current branch, and the branch is updated to point to it [git commit documentation](https://git-scm.com/docs/git-commit)

``` git push```
Use this for publishing your revisions.

## Instructions
1.After followingg the tutorial, compare the view of commit history in terminal versus in GitHub Desktop.
2.Fork your own and upload files, relate Git commands to the data model.

## Additional
### Links
- Use version control in IntelliJ and more in-depth explanation for committing/pushing/pulling
[CSE 373]https://courses.cs.washington.edu/courses/cse373/20au/projects/cse143review/submit/#committing
- This entire series covers tools seldom introduced in cs classes, lecture 6 is specific on Version Control (Git) 
[Git's data model] (https://missing.csail.mit.edu/2020/version-control/)

### Notes
1. There is an exception for the quoted sentences in ``` git commit```, which is when no branch is associated with the working tree, in which case HEAD is "detached".
2. The commands can be followed by different options. Prefixed by -. 
3. If you have no previous experience with Git, it's recommended to read the first few chapters in [Pro Git](https://git-scm.com/book/en/v2).
