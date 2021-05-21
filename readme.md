# Undoing

## checkout --> revert --> reset

git checkout commitId

git revert commitId

git reset commitId

# Branching

## Too list all branches

git branch -a

## To switch branch

git checkout branchName

### Shorthand for above 2 steps

git checkout -b branchName

(it will create new branch and checkout (switch to it))

## To delete branch before merge

git branch -D branchName

## To merge branch

(first go to that branch you want to merge ie master)

git merge branchName

## Conflict moment

git add .
git commit (This is merge commit so we dont need to write commit message beside it but in vscode)

## To delete branch after merge

git branch -d branchName

## Alias(whe we are creating repo on our machine)

git remote add origin repositoryUrl

git push origin master

## Pull request

(to keep files are up to date if any developer made changes in master branch)

git pull origin master