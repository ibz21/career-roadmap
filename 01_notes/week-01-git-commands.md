# Week 1 - Git Commands



## What this file is for

This file records the basic Git commands I have used so far, what they mean, their syntax, and why they are useful.



---



## `git --version`

**Meaning:** Show the installed Git version.  

**Used for:** Checking that Git is installed and available.



**Syntax:**

```powershell

git --version

```



**Examples:**

```powershell

git --version

```



**Why it matters:**  

This confirms Git is installed before trying to use it.



---



## `git status`

**Meaning:** Show the current state of the repository.  

**Used for:** Checking what files are untracked, staged, or modified.



**Syntax:**

```powershell

git status

```



**Examples:**

```powershell

git status

```



**Why it matters:**  

This is one of the most important Git commands because it shows what Git thinks is happening in the project.



---



## `git init`

**Meaning:** Initialize a Git repository.  

**Used for:** Turning a normal folder into a Git-tracked project.



**Syntax:**

```powershell

git init

```



**Examples:**

```powershell

git init

```



**Why it matters:**  

This creates the hidden `.git` folder and starts version control in the project.



---



## `git add .`

**Meaning:** Stage all changes in the current folder.  

**Used for:** Preparing changes for the next commit.



**Syntax:**

```powershell

git add .

```



**Examples:**

```powershell

git add .

```



**Why it matters:**  

This moves changes into Git’s staging area so they can be included in the next commit.



---



## `git commit -m "message"`

**Meaning:** Save a checkpoint in Git history with a message.  

**Used for:** Recording a version of the project.



**Syntax:**

```powershell

git commit -m "Your commit message"

```



**Examples:**

```powershell

git commit -m "Initial career roadmap setup"

git commit -m "Add repository README"

git commit -m "Add Week 1 PowerShell commands notes"

```



**Why it matters:**  

This creates a named save point in the Git history.



---



## `git remote add origin <repo-url>`

**Meaning:** Connect the local repository to a remote GitHub repository.  

**Used for:** Linking the local project to GitHub.



**Syntax:**

```powershell

git remote add origin https://github.com/username/repo-name.git

```



**Examples:**

```powershell

git remote add origin https://github.com/ibz21/career-roadmap.git

```



**Why it matters:**  

This creates the link between the local repo and the online GitHub repo.



---



## `git remote -v`

**Meaning:** Show the configured remote connections.  

**Used for:** Checking which remote repository is connected.



**Syntax:**

```powershell

git remote -v

```



**Examples:**

```powershell

git remote -v

```



**Why it matters:**  

This lets me confirm the local repo is linked to the correct GitHub repo.



---



## `git branch`

**Meaning:** Show the current branch.  

**Used for:** Checking which branch I am working on.



**Syntax:**

```powershell

git branch

```



**Examples:**

```powershell

git branch

```



**Why it matters:**  

This helps me confirm the current working branch before pushing or making further changes.



---



## `git push -u origin master`

**Meaning:** Push the current branch to GitHub and remember the upstream connection.  

**Used for:** Sending the first local commit history to GitHub.



**Syntax:**

```powershell

git push -u origin master

```



**Examples:**

```powershell

git push -u origin master

```



**Why it matters:**  

This uploads the local branch to GitHub and sets the default remote branch.



---



## `git push`

**Meaning:** Push local commits to the linked remote branch.  

**Used for:** Uploading later commits to GitHub.



**Syntax:**

```powershell

git push

```



**Examples:**

```powershell

git push

```



**Why it matters:**  

After the upstream is set, this becomes the normal way to send new commits to GitHub.



---



## Important Git ideas



### Working directory

The current files on my computer that I am editing.



### Staging area

Git’s preparation area.  

When I use `git add`, I am telling Git which changes should go into the next commit.



### Commit

A saved checkpoint in Git history.



### Remote

A connected online copy of the repository, such as GitHub.



### Branch

A line of work in the repository.



---



## Simple Git flow



- edit files locally

- stage changes with `git add`

- save a checkpoint with `git commit`

- upload to GitHub with `git push`



---



## Important ideas learned



- Git and GitHub are related but not the same thing

- Git works locally on my computer

- GitHub is the remote online copy

- `git add` stages changes

- `git commit` saves a checkpoint locally

- `git push` uploads commits to GitHub

- `git status` is one of the most useful commands because it shows the current state of the repo

