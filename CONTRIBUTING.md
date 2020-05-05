## Open for Contribution

1. Fork the repository and then clone it. For cloning command is:
```
$ git clone "https://github.com/<username>/Project-2020"
```

3. Do changes and stage them.
```
$ git add <filename>
```

4. Commit you changes with a commit message.
```
$ git commit -m "<message>"
```

5. Push changes to your forked repository
```
$ git push -u origin branchname
```
6. Create a pull request to the upstream repository.

## Synchronize forked repository with Main repository

1. Create upstream as our repository
```
$ git remote add main "https://github.com/dotQuestionmark/Project-2020"
```

2. Fetch changes from main repository
```
$ git fetch main
```

3. Merge changes after being fetched
```
$ git merge main/master
```

5. Push changes to your forked repository
```
$ git push -f origin master
```
