[Johnston - Reading Notes - Home](https://chrisjohnston1986.github.io/reading-notes/)

# Code 102, _Intro to Software Development_ 
**Class 03 - Reading Notes**

&nbsp;
&nbsp;

# Git Tutorial: A Comprehensive Guide
  
[Git Tutorial: A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

&nbsp;

## What is Version Control?

> _A Version Control is a system that allows the user to share code with others, for multiple developers to work on code simultaneously, review changes to code, and revert a file to a previous version._

**Centralized Version Control:** This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process (by eliminating the need to involve all local databases), allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges.

**Distributed Version Control:** Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines. To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information. Because the DVCS allows for multiple mirrored repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows.

&nbsp;

## What is Git?

> _Git is a Distributed Version Control system (DVCS) which is made of of file “snapshots”. It mostly uses local resources (local operations), not relying on a server or internet connection. Every change that is made to a file is tracked by Git. As the gatekeeper, Git will always detect file corruption or loss of information in transit. Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost._

_Files in Git can reside in three main states:_

**committed:** _Data is securely stored in a local database._

**modified:** _File has been changed but not committed to the database._

**staged:** _Flagged a file’s changed version to be committed in the next snapshot._

&nbsp;
&nbsp;

<hr>

# History of Git

> _Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status. Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast, Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world._

<hr>

&nbsp;

# Setting up a Git Repository

&nbsp;

## Importing
To import an existing project or directory:

- Switch to target project's directory `cd`
- Use `git init` command
- To start tracking these files

> ___git add *.c___   
> ***git add LICENSE***   
>  ***git commit -m "add a message"***

## Cloning

Create a copy of a Git repository
>***git clone(URL)***
To clone into a different directory, add the name after the URL.

&nbsp;

# Workflow

&nbsp;

## Local Repository Structure

The local Git repository has three components:
> **Working Directory**   ===>   **Index**   ===>   **Head**

- The Working Directory is where the actual files are located
- The Index is used for staging changes
- The Head points to the most recent commit

## Saving Changes

**tracked:** _Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot._

**untracked:** _Untracked files were not in the last snapshot and do not currently reside in the staging area._

> After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.

## ACP
ACP refers to the process of ADDING, COMMITTING, and PUSHING changes from your local drive to the live project.

- Clone file from GitHub with ***git clone (URL)***
- Open VSC with ***code .***
- **ADD** changes to your file in VSC, then Ctrl+S to Save
- In the Terminal,  ***git add (name of file that was changed)*** 
- Check status with ***git status***
- **COMMIT** changes and leave a message ***git commit -m "leave a PUBLIC informational message here"***
- To **PUSH** changes to live site, use ***git push origin main***

&nbsp;
&nbsp;

[https://chrisjohnston1986.github.io/reading-notes/102class03reading](https://chrisjohnston1986.github.io/reading-notes/102/102class03reading.html)
