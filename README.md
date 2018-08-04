# My useful git commands
Useful git commands 


## Table of contents

- [How to see my last commit](#howt-to-see-my-last-commit)
- [How to output git log with the first line only?](#how-to-output-git-log-with-the-first-line-only)
- [How can i view a git log of just one users](#how-can-i-view-a-git-log-of-just-one-user)

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

## How can i view a git log of just one users

This command is useful to see log by particular user

```md
git log --author="vidhya"
```

will match a commit made by "Vidhyadharan Deivamani" and also

```md
git log --author=deiva
```

<a href="https://stackoverflow.com/questions/4259996/how-can-i-view-a-git-log-of-just-one-users-commits?answertab=active#tab-top">credits</a>
