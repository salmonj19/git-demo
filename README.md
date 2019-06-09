# Practice repository to start learning.

git init // init a new git repository
git status // show status of working branch
git add // add files to staging area
git commit -m "<message>" // obvious
git branch // create a branch
git log // get a history of the commits
git log --all
git log --author "<name>"
git log --since "<date>"
git log --until "<date>"
git log --oneline
git log --oneline --graph --all
git merge // merge changes from one branch to master, or another branch

# Another section for the merge branch
- A fast-forward commit just points to the latest commit.
- Automatic merge happens when changes have happened but git can reconcile the changes into a single commit.

git checkout -b new-name // create and switch to a branch

git stash // save changes to current branch without committing
git stash list // show saved changes
git stash pop // bring changes back

git show <commit> // show diff of a commit
git diff // working vs commit
git diff // changes that will be committed

