# git status

Check current status

### Command

```sh
> git status
```

### Example

1. Check current status

```sh
> git status
```

Result:

```sh
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
```

> There is nothing to commit

2. Edit any file or create a new file

3. Check current status again

```sh
> git status
```

Result:

```sh
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   server/__init__.py

no changes added to commit (use "git add" and/or "git commit -a")
```

The file ```server/__init__.py``` was edited as an example, so it will listed as modified file
