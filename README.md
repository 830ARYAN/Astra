# Astra
## Step 1: Create a new repository from GitHub

## Step 2: Open VS Code and connect the repository
```bash
git clone <Link>
## Initialize an existing directory as a Git repository
git init

# Retrieve an entire repository from a hosted location via URL```
git clone [url]

Stage & Snapshot
Show modified files in working directory, staged for your next commit
git status

Add a file as it looks now to your next commit (stage)
git add [file]
or git add .

Unstage a file while retaining the changes in working directory
git reset [file]


Diff of what is changed but not staged
git diff


Diff of what is staged but not yet committed
git diff --staged

Commit your staged content as a new commit snapshot
git commit -m “[descriptive message]”


## Step 1: Create a new repository from GitHub

## Step 2: Open VS Code and connect the repository
```bash
git clone <Link>
Step 3: Setup & Init
Configuring user information, initializing and cloning repositories.

Initialize an existing directory as a Git repository

git init
Retrieve an entire repository from a hosted location via URL

git clone [url]

Stage & Snapshot
Working with snapshots and the Git staging area.

Show modified files in working directory, staged for your next commit

git status
Add a file as it looks now to your next commit (stage)

git add [file]
Unstage a file while retaining the changes in working directory

git reset [file]
Diff of what is changed but not staged

git diff
Diff of what is staged but not yet committed

git diff --staged
Commit your staged content as a new commit snapshot

git commit -m “[descriptive message]”

Branch & Merge
List your branches. A * will appear next to the currently active branch
git branch

Create a new branch at the current commit
git branch [branch-name]

Switch to another branch and check it out into your working directory
git checkout [branch-name]

Merge the specified branch’s history into the current one
git merge [branch]

Show all commits in the current branch’s history
git log

Show the commit history for the currently active branch
git log

Show the commits on branchA that are not on branchB
git log branchB..branchA

Show the commits that changed file, even across renames
git log --follow [file]

Show the diff of what is in branchA that is not in branchB
git diff branchB...branchA

Show any object in Git in human-readable format
git show [SHA]

Share & Update

Add a git URL as an alias
git remote add [alias] [url]

Fetch down all the branches from that Git remote
git fetch [alias]

Merge a remote branch into your current branch to bring it up to date
git merge [alias]/[branch]

Transmit local branch commits to the remote repository branch
git push [alias] [branch]

Fetch and merge changes from the remote repository to the local branch
git pull


Rewrite History
Rewriting branches, updating commits, and clearing history.

Apply any commits of current branch ahead of specified one
git rebase [branch]


Clear staging area, rewrite working tree from specified commit
git reset --hard [commit]

You can now copy this entire block and paste it wherever you need it.









