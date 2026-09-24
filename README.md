#git-nn
# Git Branching Practice

This repository demonstrates practical Git branching and remote repository operations using GitHub.

## Topics Practiced

* Git Branch
* Git Switch
* Git Checkout
* Git Status
* Git Add
* Git Commit
* Git Merge
* Git Rebase
* Git Revert
* Git Cherry-pick
* Git Push
* Git Pull
* Git Fetch
* Git Log

## Practical Activities

### 1. Git Branching

Created and worked with multiple branches:

* `main`
* `feature/login`
* `feature/register`
* `feature/profile`
* `feature/payment`

Created separate files and commits in the feature branches and verified the changes by switching between branches.

### 2. Git Merge

Merged the `feature/login` branch into `main` and verified the commit history using:

```bash
git merge feature/login
git log --oneline --graph --all
```

### 3. Git Rebase

Created a feature branch, added commits, updated the `main` branch, and rebased the feature branch with the latest `main` changes.

```bash
git rebase main
```

### 4. Git Revert

Created and pushed a commit, then reverted the commit using:

```bash
git revert HEAD
```

The original commit remained in the Git history while a new revert commit reversed its changes.

### 5. Git Cherry-pick

Created multiple commits on a feature branch and applied one specific commit to another branch using:

```bash
git cherry-pick <commit-id>
```

This demonstrated how to apply a selected commit without merging the entire branch.

### 6. Git Push

Uploaded local commits and branches to GitHub using:

```bash
git push
git push origin main
```

### 7. Git Fetch

Retrieved changes from the remote repository without automatically merging them:

```bash
git fetch origin
```

### 8. Git Pull

Fetched and integrated remote changes into the current branch:

```bash
git pull origin main
```

## Git History Verification

The complete branch and commit history was verified using:

```bash
git log --oneline --graph --all
```

## Repository

GitHub Repository:

`https://github.com/YOUR_USERNAME/git-branching-practice`

## Conclusion

This project demonstrates practical usage of Git branching, merging, rebasing, reverting, cherry-picking, pushing, pulling, and fetching with a GitHub remote repository.

