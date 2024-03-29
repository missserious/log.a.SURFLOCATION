```
$ git add -A
```

```
$ git commit -m "Describe your commit"
```

go to previous commit:

```
$ git reset --hard HEAD
```

show all commits:

```
$ git log
```

reset to a specific commit by using commitID

```
$ git reset --hard 096f0cc34d6119ff23d060ba4d4525b9999d846e
```

shows all branches:

```
$ git branch
```

create new branch called: new-feature

```
$ git branch new-feature
```

```
$ git merge new-feature
```

```
$ git checkout new-feature
```

You can change the latest commit message using the

```
$ git commit --amend
```

Summarise commits that have already been sent:
https://fryboyter.de/git-bereits-gesendete-commits-zusammenfassen/

```
$ git rebase -i HEAD~X
```
