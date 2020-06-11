yum install git-all
mkdir -p ~/code/git-practice

## Coomands used
git init: Create a repository
git status: Compare working directory, staging area, and current branch
git add: Add changes from working directory to staging area
git commit: Commmit changes from staging area to current branch
git config --global user.email "robert@abc.com"
git config --global user.name "Robert V"
git commit -m "Message / description of git commands; don't end with ."  "This commit will ..."
git config: Set or get configuration
git log: Show history of project commits
git branch: List branches
git checkou -b : Create branch, then check it out
git stash: Stash changes from working directory
git stash list: List stashes
git stat pop:  Apply stashed changes to workig directory
git branch -v: Display Last commits in branches
git log: Show history of project commits
git log --oneline
git log --oneline --graph --all
git show: Show a single commit
git diff: Show the difference betweencommits, the working directory, and the staging area
git diff --cached
git diff master log-show-diff
git diff master
git help diff
git merge nameofbranche: Merge changes from different branches
git remote add origin https://github.com/user/repository.git:Add new remote
git remote -v: List remote repositories 
git push -u origin master 
git push
git pull


## Resolving Merge Conficts
git diff, git add, git commit
git merge --abort: Abort an in-progress merge
git log branch1..branch2: Log of commits in branch2 tehat don't ecist in branc1
git log branch1...branch2: Log of commits in either branch but not both
git merge --no-commit  -no-off: Attempt to merge , but don't create an auto merge or ff merge
git branch --no-merged branch1: List branches that have unmerged commits
git branch --merget master: List branches that have no unmerged commits

## Other
git diff --unified=0 1b0768c b8e70b0
