Git assignment
List of Git commmands
✅ Setup & Configuration
git init — Initialize a new repository 
git clone <url> — Clone a remote repository 
git config --global user.name "Name" — Set username 
git config --global user.email "email" — Set email 
✅ Staging & Committing
git status — Show working tree status 
git add <file> — Stage a file
git add . — Stage all changes
git add -p — Interactively stage hunks 
git commit -m "msg" — Commit staged changes
git commit --amend — Modify last commit 
✅ Branching
git branch — List branches
git branch <name> — Create branch
git switch <name> — Switch branches 
git checkout -b <name> — Create & switch
git branch -d <name> — Delete branch
git branch -D <name> — Force delete 
✅ Merging & Rebasing
git merge <branch> — Merge branch 
git merge --no-ff <branch> — Force merge commit
git rebase <branch> — Reapply commits on another branch
git rebase --abort — Cancel rebase
✅ Remote Repositories
git remote -v — List remotes
git remote add origin <url> — Add remote
git fetch — Download changes without merging
git pull — Fetch + merge
git push — Upload commits
git push -u origin <branch> — Push & set upstream 
gitcheatsheets.org
gitcheatsheets.org
✅ Stashing
git stash — Save uncommitted changes
git stash list — List stashes
git stash pop — Apply & remove latest stash
git stash drop — Delete stash
✅ History & Inspection
git log — View commit history
git log --oneline --graph — Compact graph view 
git show <commit> — Show commit details
git diff — Show unstaged changes
git diff --staged — Show staged changes
git blame <file> — Show who changed each line
✅ Undoing Changes
git restore <file> — Discard working directory changes 
git reset <file> — Unstage file
git reset --soft HEAD~1 — Undo commit, keep changes
git reset --hard HEAD — Reset to last commit
git revert <commit> — Create a revert commit
✅ Tags
git tag — List tags
git tag v1.0.0 — Create tag
git push --tags — Push all tags 