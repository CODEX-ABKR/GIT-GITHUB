# Git/Github

A repo covering basic concepts of Git and Github

## CMD Commands

- Selecting drive: `[drive-name:] :` (eg: E:) `IMP`

- Going back one folder: `cd ..`

- Going back two folders: `cd ../..`

- Going to desired folder in the current directory: `cd home => cd (my-dir)` (Use tab to get full name of directory)

- To list the contents of current folder: `ls` or `dir`

- To create new directory: `mkdir (my-dir)` (name of the directory)

- To delete a directory: rmdir my-dir (name of the directory)

- To create new file: `touch [my-dir]` (name of the file)

- To delete a file: rm `[my-dir]` (name of the file)

- To open a new file with the Text editor: `[text-editor]` (name of the editor) `[my-dir]` (name of the file)

To remove the scary screen: `:wq`

## Git Commands

- To set the author globally for all repos in machine, configure user name and user email:

  `git config --global [user.name]`

  `git config --global [user.email]`

- To set the author for current repo, configure user name and user email:

  `git config [user.name]`

  `git config [user.email]`

- To check who is making changes: `git config user.name`

- Checking the status of a file:
`git status`

- Initializing git repo: `git init` (used so git can track any changes made)

- Adding a file to staging area: `git add [my-dir]` (name of the file)

- Removing a file from staging area: `git reset [my-dir]` (name of the file) or `git rm --cached [my-dir]` (name of the file)

- Adding all files in staging area at once: `git add .`

- Making commit: `git commit -m "added [my-dir] and
[my-dir-2]"` (any message explaining work done in commit)

- To see commit history: `git log`

- To see commit history in short: `git log --oneline`

- Checkout commit: `git checkout [commit-id]` eg:4eb87b3 (takes to desired point in time, does not change commit history, perfectly safe)

- Revert commit: `git revert [commit-id]`
eg:4eb87b3 (to undo a particular commit, not completely safe)

- Reset commit: `git reset [commit-id] ` eg:4eb87b3 (permanently takes to desired point in time, unsafe)

- Pushing from local repo to remote repo: `git push [url]` (url of repo to which the code is to be pushed) `[branch-name]` (the branch which is to be pushed up) or `git push origin [branch-name]` (if repo is assigned an alias) or `git remote -v` (use if repo is cloned)

- Pulling from remote repo to local repo: `git pull [branch-name]`

- Giving remote repo an alias: `git remote add origin [url]`

- Cloning a repo: `git clone [url]`

- To remove changes from text editor: `git reset [commit-id] --hard`

### Branches

- Creating and selecting a new branch: `git Checkout -b [branch-name]` (short method)

- Creating new branch: `git branch [branch-name]`

- Selecting a branch: `git Checkout [branch-name]`

- Viewing all branches: `git branch -a`

- Deleting a branch: `git branch -D [branch-name]` or `git branch -d [branch-name]` (works if branch is fully merged)

- Merging a branch: `git merge [branch-name]` (first select the branch to which it is to be merged)

- Keeping files locally up to date with remote repo: `git pull origin master`
# Important

## CMD Commands

- Selecting drive: `[drive-name:] :` (eg: E:)

- Going back one folder: `cd ..`

- To list the contents of current folder: `ls` or `dir`

- Checking the status of a file:
`git status`
- CD `[MY DIR]/`

## Git Commands

- Adding all files in staging area at once: `git add .`

- Making commit: `git commit -m "added [my-dir]"`

- Giving remote repo an alias: `git remote add origin [url]`

- Pushing from local repo to remote repo: `git push [url]` (url of repo to which the code is to be pushed) `[branch-name]` (the branch which is to be pushed up) or `git push origin [branch-name]` (if repo is assigned an alias)


