\# Week 1 - Bandit



\## What this file is for

This file tracks my Bandit progress for Linux command-line practice during Week 1.



\## Day 2



\### Level 0

\*\*Goal:\*\* Log in to the Bandit server as `bandit0`.



\*\*What I did:\*\*

\- connected to the remote server using SSH

\- logged in as `bandit0`

\- checked my location with `pwd`

\- listed files with `ls`

\- checked the user with `whoami`

\- used `cat readme` to read the file

\- retrieved the password for Level 1



\*\*Commands used:\*\*

```bash

ssh bandit0@bandit.labs.overthewire.org -p 2220

pwd

ls

whoami

cat readme

```



\*\*What I learned:\*\*

\- SSH is used to connect to a remote machine

\- `pwd` shows the current location

\- `ls` shows the files in the current folder

\- `whoami` shows the current user

\- `cat` prints the contents of a file to the terminal



\*\*Important note:\*\*

Do not store Bandit passwords in this GitHub repo.



\---



\### Level 1

\*\*Goal:\*\* Log in as `bandit1` using the password found in Level 0.



\*\*What I need to do next:\*\*

\- exit the current session

\- connect as `bandit1`

\- inspect the files in the home directory

\- work out how to read the file for the next password



\*\*Commands to start Level 1:\*\*

```bash

exit

ssh bandit1@bandit.labs.overthewire.org -p 2220

pwd

ls

```



\## Key learning so far

\- each Bandit level is a different user account

\- the password found in one level is used to log into the next level

\- Linux command-line work feels more real when done as a challenge instead of only reading notes

