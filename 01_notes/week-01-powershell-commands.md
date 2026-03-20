# Week 1 - PowerShell Commands



## What this file is for

This file records the basic PowerShell commands I have used so far, what they mean, their syntax, and why they are useful.



---



## `cd`

**Meaning:** Change directory.  

**Used for:** Moving into another folder.



**Syntax:**

```powershell

cd folder-name

cd "Folder Name With Spaces"

cd ..

```



**Examples:**

```powershell

cd 01\_notes

cd "Career Roadmap"

cd ..

```



**Why it matters:**  

This is one of the main ways to move around the folder structure in the terminal.



---



## `dir`

**Meaning:** Directory listing.  

**Used for:** Showing the files and folders in a location.



**Syntax:**

```powershell

dir

dir .\\01\_notes

```



**Examples:**

```powershell

dir

dir .\\00\_admin

```



**Why it matters:**  

This lets me inspect what is inside the current folder or another folder.



---



## `mkdir`

**Meaning:** Make directory.  

**Used for:** Creating a folder.



**Syntax:**

```powershell

mkdir folder-name

mkdir .\\parent-folder\\new-folder

```



**Examples:**

```powershell

mkdir 00\_admin

mkdir .\\02\_labs

mkdir .\\02\_labs\\powershell

```



**Why it matters:**  

This is how I create project structure from the terminal.



---



## `New-Item`

**Meaning:** Create a new item.  

**Used for:** Creating a file or folder.



**Syntax:**

```powershell

New-Item file-name -ItemType File

New-Item .\\folder\\file-name.md -ItemType File

```



**Examples:**

```powershell

New-Item goals.md -ItemType File

New-Item .\\01\_notes\\week-01-git-commands.md -ItemType File

```



**Why it matters:**  

This is how I create files directly from PowerShell.



---



## `pwd`

**Meaning:** Print working directory.  

**Used for:** Showing my current location in the terminal.



**Syntax:**

```powershell

pwd

```



**Examples:**

```powershell

pwd

```



**Why it matters:**  

This helps me confirm exactly where I am before creating, moving, or editing files.



---



## `Copy-Item`

**Meaning:** Copy a file or folder.  

**Used for:** Making a duplicate of something.



**Syntax:**

```powershell

Copy-Item source destination

```



**Examples:**

```powershell

Copy-Item .\\05\_weekly\_reviews\\week-01-review.md .\\05\_weekly\_reviews\\week-01-review-backup.md

```



**Why it matters:**  

This is useful for backups, templates, and duplicate files.



---



## `Move-Item`

**Meaning:** Move or rename a file or folder.  

**Used for:** Changing where something lives or changing its name.



**Syntax:**

```powershell

Move-Item source destination

```



**Examples:**

```powershell

Move-Item .\\01\_notes\\temp-file.md .\\01\_notes\\temp-file-renamed.md

```



**Why it matters:**  

This helps me reorganize files and also acts like a rename command.



---



## `Remove-Item`

**Meaning:** Remove or delete a file or folder.  

**Used for:** Deleting something I no longer want.



**Syntax:**

```powershell

Remove-Item path

```



**Examples:**

```powershell

Remove-Item .\\01\_notes\\temp-file-renamed.md

```



**Why it matters:**  

This is how I remove files directly from the terminal.



---



## Important path ideas



### `.`

**Meaning:** The current location.



**Examples:**

```powershell

dir .

git add .

```



**Why it matters:**  

This tells the command to work from where I am now.



---



### `..`

**Meaning:** The folder above the current one.



**Examples:**

```powershell

cd ..

```



**Why it matters:**  

This is how I move up one level in the folder structure.



---



### `.\\folder\\file-name`

**Meaning:** A path starting from the current location.



**Examples:**

```powershell

notepad .\\01\_notes\\week-01-linux-git.md

dir .\\00\_admin

New-Item .\\01\_notes\\week-01-powershell-commands.md -ItemType File

```



**Why it matters:**  

This lets me target another file or folder directly without moving into it first.



---



## Important ideas learned



- A directory means a folder

- The terminal always has a current location

- I can move between folders using `cd`

- I can inspect folders using `dir`

- I can create folders using `mkdir`

- I can create files using `New-Item`

- I can copy files using `Copy-Item`

- I can move or rename files using `Move-Item`

- I can delete files using `Remove-Item`

- I can target another folder directly by using its path

