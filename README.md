# Repo-Basics
Understanding commits, content changes and HEAD

### How do you see the files changed within each commit from git log?
https://www.youtube.com/watch?v=Ew8HQsFyVHo&feature=youtu.be

Type in "git status" to see if there are any changes not staged for commit.
Type in "git add <file>"  to include in what will be committed.

Type in "git log" and you will see a list of changes in chronological order.
https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History

**For full path names of changed files:**
git log --name-only

**For full path names and status of changed files:**
git log --name-status

https://stackoverflow.com/questions/1230084/how-to-have-git-log-show-filenames-like-svn-log-v

### How do you see the contents of what changed within each file from the git log?
Type in "git diff" to see your changes.

https://www.youtube.com/watch?v=RXSriVcoI70&t=19s


### What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within a merge conflict)

The HEAD in Git is the pointer to the current branch reference, which is in turn a pointer to the last commit you made or the last commit that was checked out into your working directory. That also means it will be the parent of the next commit you do. It's generally simplest to think of it as HEAD is the snapshot of your last commit.

Source: https://stackoverflow.com/questions/2529971/what-is-the-head-in-git
