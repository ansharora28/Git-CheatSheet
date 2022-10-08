# WELCOME TO THE GIT CHEAT SHEET

    AUTHOR:         EshanTrivedi2, Arya-A-Nair and VinayKanase
    REFERENCE:      Git-Github Bootcamp (Colt Steele) Udemy
    DESCRIPTION:    Your very own Git and Github Cheatsheet!

## TERMINAL BASICS

**It is the LIST command which LISTS all the contents of a Directory**

```bash
$ ls
```

**LOCATES to a directory and then LISTS the contents**

```bash
$ ls foldername
```

**Print Working Directory**

```bash
$ pwd
```

**CHANGES and HOPS onto the respective Working Directory**

```bash
$ cd C:\User\UserName\foldername
```

**HOPS to Parent Directory**

```bash
$ cd ..
```

**CLEARS the Used Terminal**

```bash
$ clear
```

**QUITS out of a command**

```bash
$ q
```

**CREATES an Empty directory inside the Working Directory**

```bash
$ mkdir foldername
```

**DELETES the file**

```bash
$ rm filename
```

**DELETES the directory**

```bash
$ rm -rf foldername
```

**OPENS the File Explorer to the ROOT Directory**

```bash
$ start .
```

## SETTING GIT USER NAME AND EMAIL

**to CHECK if git User-Name is set**

```bash
$ git config user.name
```

**to CHECK if git User-Email is set**

```bash
$ git config user.email
```

**To SET or CHANGE git User-Name**

```bash
$ git config --global user.name "Eshan Trivedi"
```

**To SET or CHANGE git User-Email**

```bash
$ git config --global user.email eshan.trivedi.9@gmail.com
```

**to SET or CHANGE default code editor as VsCode**

```bash
$ git config --global core.editor "code --wait"
```

**to CHANGE git User-Name and git User-Email directly in the config file using vim**

```bash
$ git config --global --edit
```

**To EXIT vim**

```bash
$ `escape key` + :wq
```

## GETTING GIT HELP

**Use for more details and examples on any of the below (or above) commands e.g. push, pull etc.**

```bash
$ git command --help
```

## CREATING A GIT REPOSITORY

`STEP 1:` **INITIALIZES an empty repository**

```bash
$ git init
```

`STEP 2:`  **to CHECK the status of a repository, a .git directory is created, all git history is deleted if .git directory is deleted**

```bash
$ git status
```

## STAGING FILE/FILES OF THE REPOSITORY:

**to KEEP A TRACK of modifications or changes**
**STAGES the file**

```bash
$ git add filename.txt
```

**UN-STAGES the file**

```bash
$ git rm --cached filename.txt
```

**STAGES all files in the repository**

```bash
$ git add --all
    OR
$ git all .
    OR
$ git add .
```

## COMMITING A COMMIT:

**COMMITS the STAGED files with a commit message**

```bash
$ git commit -m "commit message"
```

**SKIPS the Staging part and directly COMMITS**

```bash
$ git commit -a -m "commit message"
```

**LOGS all the commits done to the repository**

```bash
$ git log
```

**LOGS commits in a single line**

```bash
$ git log --oneline
```

**AMMENDS the previous commit**

```bash
$ git commit --ammend
```

**LOGS the changes**

```bash
$ git diff
```
## UNDOING CHANGES:

**Creating a commit that undoes all changes made in <commit>**
    
```bash
$ git revert <commit>
```
    
**Remove <file> from staging area keeping working directory unchanged**
    
```bash
$ git reset <file>
```


