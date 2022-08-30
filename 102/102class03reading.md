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

## What is Git?

> _Git is a Distributed Version Control system (DVCS) which is made of of file “snapshots”. It mostly uses local resources (local operations), not relying on a server or internet connection. Every change that is made to a file is tracked by Git. As the gatekeeper, Git will always detect file corruption or loss of information in transit. Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost._

_Files in Git can reside in three main states:_ **committed, modified and staged.**

**committed:** Data is securely stored in a local database.

**modified:** File has been changed but not committed to the database.

**staged:** Flagged a file’s changed version to be committed in the next snapshot

&nbsp;
&nbsp;

<hr>

# History of Git

> _Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status. Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast, Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world._

&nbsp;
&nbsp;

[https://chrisjohnston1986.github.io/reading-notes/102class03reading](https://chrisjohnston1986.github.io/reading-notes/102/102class03reading.html)
