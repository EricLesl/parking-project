## Set up

1. fork it & clone it on your local computer
2. cd parking-project
3. git remote add upstream https://github.com/pkboom/parking-project
4. git remote -v
5. if you see something like this below, then you're all set.

```
origin https://github.com/(your-github-id)/parking-project.git (fetch)
origin https://github.com/(your-github-id)/parking-project.git (push)
upstream https://github.com/pkboom/parking-project (fetch)
upstream https://github.com/pkboom/parking-project (push)
```

## Before you start working

1. git checkout -b your-branch-name

## If you've finished your work,

> You can git add & git commit as many times as you want.

1. git add .
2. git commit -m 'your job desciption'
3. git push origin your-branch-name
4. go to your github
5. create a pull request

## Sync your fork with the main repository

> Or when I say 'pull it'

1. git checkout master
2. git fetch upstream
3. git rebase upstream/master
4. git push

## If your branch is no longer needed

> Or when I say 'You branch is merged'

1. git branch -d your-branch-name
2. git push origin --delete your-branch-name

## Some git commands

-   git status
-   git log --decorate --oneline --graph --all

[Source: https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940)
