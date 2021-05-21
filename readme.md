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

## To delete branch after merge
