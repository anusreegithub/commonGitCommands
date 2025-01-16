# commonGitCommands
Repository for common git commands - Helpful git commands

1. Initalizing the repository
```
git init
```

2. Making the copy of the existing reposiory into local
```
git clone repoURL
```

3. Shows the status of changes as untracked, modified or staged
```
git status
```

4. Staging the changes
```
git add .
```
```
git add file
```

5. Recording the current changes into the repository
```
git commit -m "message"
```

6. Displaying the committed history with message
```
git log
```
7. For listing all the branches in the repository

```
git branch
```
8. For creating new branch

```
git branch branchName
```

9. For switching to specific branch

```
git checkout branchName
```

10. Merging a branch with current branch
```
git merge branchName
```
11. If there is project in our local, and we want to add that in a repository

```
git remote add origin url
```

12. Retrives the updaes from the repo

```
git fetch
```

13. Retrives updates and automatically applies that change to our branch
```
git pull
```

14. Updates the current changes into the repo
```
git push
```

15. To see exactly what modifications you made to a file since the last commit.
```
git diff
```

16. Removes a file from the staging area.
```
git reset file
```

17. adds a new commit that effectively "cancels" the changes from the earlier commit.
```
git revert


These are the common git commands needed to learn as a beginner