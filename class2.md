# Class 2 - Reading Notes

# The Coder's Computer

[Choosing a Text Editor - The Older Coder](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf)

> _choosing a text editor ends up being a very personal choice_

## What is a text editor?

> _piece of software that you download and install on
your computer, or you access online through your web browser, that
allows you to write and manage text, especially the text that you write
to build a web site._

### What features should I look for?

- code completion
- syntax highligting
- nice variety of themes
- ability to choose fom a healthy selection of extension available, when you need them

**Code Completion** 

> _Code completion allows you to start typing, and the code completion
feature will display possible suggestions based on what you originally
typed. This saves you time by providing a choice, rather than allowing
you to finish typing and possibly encounter typos. Also, some code completion includes the closing of tags when you open them, or the closing of brackets when you open them, or the closing of quotation marks when you open them, thus making sure you’re always writing your code._

**Syntax Highlighting** 

> _Syntax highlighting is a feature that takes the text you
type, and makes it more noticeable by colorizing the text. Attributes
are a different color than elements. And elements are a different color
than copy. This makes it so much easier when you’re looking for an
error and you can’t find it. As well as making your text easier to read._

## Using The Software That Already Comes With Your Computer?

**Mac computers:** _Text Edit_

**Windows computers:** _Notepad_

**Linux computers:** _Gedit_

> **Usually, the text editors that come on your computer don’t have many features.**

***If using text editors on your computer:***

> - _Make sure that when you use the text editor that comes on your computer, that you’re creating code in a plain text editor. You should not see options for making text bold, underlined, or italic. Plain text has no formatting options. There is no need to bold, underline or italicize code. If you can make your text bold, underlined or italic, then you might need to change a setting somewhere. Please make sure you’re coding in plain text._ 

> - _Also, make sure that when you use the text editor that comes on your computer, that you first create a folder on your computer somewhere (maybe on your Desktop, for example) to store your entire website. As you create new documents with the text editor that comes on your computer, save those files in the appropriate folders or sub-folders within the main website folder._ 

> - _Also, please make sure that when you’re saving your file, that they have the appropriate extension at the end of the file names. For example, your main HTML file should be called, “index.html.” Your CSS file should be called something like “style.css.” The filename isn’t as important as the extension (the “.html” and the “.css”)._

## Third-Party Options

- Notepad++
- TextWangler/BB Edit
- Visual Studio Code
- Atom
- Brackets
- Sublime Text

## The Difference Between Text Editors and IDEs

> - _A text editor kind of gives away what it does in the title—it edits text. It also manages text, and manages files._

***see above examples***

> - _An IDE (Integrated Development Environment) is really a suite of different software all coming together. An IDE is a text editor, a file manager, a compiler, and a debugger all in one software package._

***think "Microsoft Outlook"***




# The Command Line

[The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)

## What are they exactly?

**Command line**

> _Text based interface to the system (terminal). You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text._

> _The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands._

*COMMAND - OUTPUT - PROMPT*

## Opening a terminal

**Mac computers:** _Terminal(app) Applications -> Utilities_

**Windows computers:** _must utilize SSH client "Putty"_

**Linux computers:** _Applications -> System or Applications -> Utilities_

## The Shell, Bash

**Shell**

> _Part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell._

> _If you would like to know which shell you are using you may use a command called echo to display a system variable stating your current shell. **Echo** is a command which is used to display messages._

## Shortcuts

> _When you enter commands, they are actually stored in a history. You can traverse this history using the up and down arrow keys. So don't bother re-typing out commands you have previously entered, you can usually just hit the up arrow a few times. You can also edit these commands using the left and right arrow keys to move the cursor where you want._




# Basic Navigation

[Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)

## Where are we?

**pwd**

> _**Print Working Directory:** identifies your current or present working directory._

## What's in our current location?

**ls**

> _**List**_ 

## Paths

> _Whenever we refer to either a file or directory on the command line, we are in fact referring to a path. ie. A path is a means to get to a particular file or directory on the system._

**Absolute and Relative Paths**

> _Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path (either way, the system will still be directed to the same location)._

> _To begin with, we have to understand that the file system under linux is a hierarchical structure. At the very top of the structure is what's called the ***root*** directory. It is denoted by a single slash ( / ). It has subdirectories, they have subdirectories and so on. Files may reside in any of these directories._

> _**Absolute path:** specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )_

> _**Relative path:** specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash._

**More on paths**

> _**~** **(tilde):** This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or /Documents._

> _**.** **(dot):** This is a reference to your current directory._

> _**..** **(dotdot):** This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory._

> _You can use any method you like to refer to a location. Whenever you refer to a file or directory on the command line you are actually referring to a path and your path can be constructed using any of these elements. The best approach is whichever is the most convenient for you._

## Let's move around a bit

> _**cd [location]:** In order to move around in the system we use a command called cd, which stands for **change directory**._ 

## Shortcuts

> _If you run the command cd without any arguments then it will always take you back to your home directory.The command cd may be run without a location as we saw in the shortcut above but usually will be run with a single command line argument which is the location we would like to change into. The location is specified as a path and as such may be specified as either an absolute or relative path and using any of the path building blocks mentioned above._

> _**Tab completion:** When you start typing a path (anywhere on the command line, you're not just limited to certain commands) you may hit the Tab key on your keyboard at any time which will invoke an auto complete action. If nothing happens then that means there are several possibilities. If you hit Tab again it will show you those possibilities. You may then continue typing and hit Tab again and it will again try to auto complete for you._





# More About Files!

[More About Files!](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

## Everything is a file

> _We need to appreciate that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc._ 

## Linux is an extensionless system

> _**file extension:** normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes the type of file.

  - **file.exe:** an executable file, or program
  - **file. txt:** a plain text file
  - **file.png, file.gif, file.jpg:** an image

> _Under Linux the system actually ignores the extension and looks inside the file to determine the type of file/_

## Linux is case sensitive

## Spaces in names

**Quotes**

**Escape Characters**

## Hidden files and directories

### _Article Review_




[https://chrisjohnston1986.github.io/reading-notes/class2](https://chrisjohnston1986.github.io/reading-notes/class2)
