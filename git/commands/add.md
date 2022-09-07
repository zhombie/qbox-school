# git add

Add unversioned files to active changelist

### Command

```sh
> git add .
```

### Example

```server/``` is created as new folder & it will be considered as untracked files. That's why you have to add a folder to default changelist, in order to commit & push to remote repository

1. Check current status

```sh
> git status
```

Result:

```sh
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        server/

nothing added to commit but untracked files present (use "git add" to track)
```

2. Add ```server/``` to default changelist

```sh
> git add .
```

3. Check current status again

```sh
> git status
```

Result:

```sh
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   server/__init__.py
```

Dot symbol at the end of the command ```git add .``` is used to add all folder & files without filter, so all ```server/``` contents (in our situation only single ```__init__.py``` file) will be added to default changelist
