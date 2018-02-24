# Learning git

## Add remote
    git remote add origin https://github.com/user/repo.git
[Add a remote](https://help.github.com/articles/adding-a-remote/)

## My username is not linked

First, run `git config -l` to check your settings and make sure that you don't have something unexpected in there.

Use `git config --global user.email correct-email@example.com` and `git config --global user.name marcpre` to change the username


[Stackoverflow - Username is not linked](https://stackoverflow.com/questions/26004587/git-commits-are-not-getting-linked-with-my-github-account)


## Adding remote repo

1. add & commits
2. `git git remote add origin "remote_repo_url"`

[Github - Adding an existing project](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/)

## Rebaseing

`git rebase`

Rebasing is the process of moving or combining a sequence of commits to a new base commit. Rebase has a powerful history rewriting features. The primary reason for rebasing is to maintain a linear project history. For example, consider a situation where the master branch has progressed since you started working on a feature branch. 

[git rebase](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)

# Errors

## "Cannot read property 'resourceUri' of undefined"

Add the folder manually with `git add folderName/`

[Github VSCode Thread](https://github.com/Microsoft/vscode/issues/35724)

## "The current branch master has no upstream branch"

`git push -u origin master`

[Stackoverflow](https://stackoverflow.com/questions/23401652/fatal-the-current-branch-master-has-no-upstream-branch)

## "LF will be replaced by CRLF"

`git config core.autocrlf true`

[Stackoverflow](https://stackoverflow.com/questions/5834014/lf-will-be-replaced-by-crlf-in-git-what-is-that-and-is-it-important)

