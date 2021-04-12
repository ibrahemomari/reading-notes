# INTRODUCTION


|  TITLE	|  DESCRIPTION 	|
|---	|---	|
|  Prerequisites 	|  understanding of the Terminal (for Mac) or Command Line (for Windows and Linux). 	|
|  Version Control	|  is a system that allows you to revisit various versions of a file or set of files by recording changes 	|
|  Local Version Control 	|  A Local VCS entails one database on your hard disk that stores changes to files. 	|
|  Centralized Version Control 	|  This system entails a single server storing all changes and file versions, which can be accessed by various clients. 	|
|   Distributed Version Control	|  It is a system that works to save old copies of files shared between users to face any chance of failure 	|


# what is Git?

Git allows and encourages you to have multiple local branches that can be entirely independent of each other. The creation, merging, and deletion of those lines of development takes seconds.


+ Snapshots
     + stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed
+ Local Operations
     + allows for process expediency because a project’s history resides on the local disk
+ Tracking Changes
     + Every single change applied to any file or directory is tracked by Git.
+ Loss of Data
     + Git is set up to greatly minimize the possibility of irreversible damage to files
+ States
     + Committed 
     + Modified
     + Staged

![Flagged a file’s changed version to be committed](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)


` Ok , Now after install GIT to your system , you must know about commands : `

` git config ` : allows the setting of configuration variables that control aspects of Git’s operation and look. \
` git config --list ` : To check settings.\
` git help ` : to get help manual.\

+ To import an existing project or directory into Git :\
    1.change directory : ` $ cd test  `\
    2.Use the git init command : ` $ git init `\
    3.start tracking these repository files : ` $ git add *.c ` , ` $ git add LICENSE ` , ` $ git commit -m “any message here” ` .\

` $ git clone https://github.com/test mydirectory  ` To clone a repository into a directory with another name of your choosing.\

## Workflow 

![Workflow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png) \

## Saving Changes 

![Saving Changes](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png) \


` $ git status ` To determine the state of files.\
` git add filename ` Track one file only \
`$ git add *  ` rack all files in a repository \
` $ git status
On branch master
Changes to be committed:
(use "git reset HEAD ..." to unstage) `  see information regarding changes to be committed /

` $ git commit -m “made change x,y,z” ` commit the changes and record what you did within the commit message /

` $ git commit -a ` Committing All Changes \
` $ git push origin master ` Pushing Changes \
` git stash ` This command temporarily removes changes and hides them, giving you a clean working directory. \
` git stash apply `This command to retrieve the hidden changes.\

