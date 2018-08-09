# My useful git commands
Useful git commands 


## Table of contents

- [How to see my last commit](#how-to-see-my-last-commit)
- [How to output git log with the first line only?](#how-to-output-git-log-with-the-first-line-only)
- [How can i view a git log of just one user](#how-can-i-view-a-git-log-of-just-one-user)
- [How do I force git pull to overwire local files](#how-do-i-force-git-pull-to-overwire-local-files)
- [How do I determine the url of git repository](#how-do-i-determine-the-url-of-git-repository)

## How to see my last commit

This command is useful to see 'my last commit' 

```md 
`git log --name-status HEAD^..HEAD`
```

## How to output git log with the first line only?

This command is useful to print commit history by one line

```md
git log --pretty=oneline --abbrev-commit
```

## How can i view a git log of just one user

This command is useful to see log by particular user

```md
git log --author="vidhya"
```

will match a commit made by "Vidhyadharan Deivamani" and also

```md
git log --author=deiva
```

<a href="https://stackoverflow.com/questions/4259996/how-can-i-view-a-git-log-of-just-one-users-commits?answertab=active#tab-top">credits</a>

## How do I force git pull to overwire local files

This command is useful when you got git <branch> | MERGING issues

```md
git fetch --all
git reset --hard origin/master
```
or
```md
git reset --hard origin/<branch_name>
```

Note: the above command will overwrite your local files

<a href="https://stackoverflow.com/questions/1125968/how-do-i-force-git-pull-to-overwrite-local-files#8888015">credits</a>

## How do I determine the url of git repository

Get only the remote url
```md
git config --get remote.origin.url
```
or 
Get the entire url
```md
 git remote show origin
```

<a href="https://stackoverflow.com/questions/4089430/how-can-i-determine-the-url-that-a-local-git-repository-was-originally-cloned-fr?answertab=active#tab-top">credits</a>


