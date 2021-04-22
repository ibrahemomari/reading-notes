# Choosing A Text Editor

## What is a text editor?

A text editor is a piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a web site. The text editor has to be one of the most important tools you can use as an aspiring web developer.


---

Some features in text editor ? 
* code completion
* display possible suggestions based on what you originally typed.
* closing of tags when you open them.
* closing of quotation marks when you open them.
* write your HTML and CSS more efficiently.
* Syntax highlighting is a feature that takes the text you type, and makes it more noticeable by colorizing the text .

---

we can use the text editor who come with PC or laptop , or use Third-Party text editor , like :

*NotePad++, TextWrangler/BB Edit ,Visual Studio Code , Atom , Brackets , Sublime Text, *


---

# The Difference Between Text Editors and IDEs : 


A text editor kind of gives away what it does in the title—it edits text. It also manages text, and manages files. I love that name “text wrangler” because in a way that’s what really a text editor does. It wrangles your text together into something meaningful.


An IDE (Integrated Development Environment) is really a suite of different software all coming together. An IDE is a text editor, a file manager, a compiler, and a debugger all in one software package.


---


# Linux Tutorial

![Linux](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/1200px-Tux.svg.png).


### Opening a Terminal :
If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.
If on Linux then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'.
If you are on Windows and intend to remotely log into another machine then you will need an SSH client. A rather good one is Putty (free) .

### The Shell, Bash :


If you would like to know which shell you are using you may use a command called echo to display a system variable stating your current shell. echo is a command which is used to display messages.



### Shortcuts :


The terminal may seem daunting but don't fret. Linux is full of shortcuts to help make your life easier. You'll be introduced to several of them throughout this tutorial


### Basic Navigation:

`pwd `which stands for Print Working Directory

`ls` to know what is current location.

 `pwd` to see the full path 

`cd` Change Directories - ie. move to another directory.

### More About Files :

everything is actually a file in Linux .

This one can sometimes be hard to get your head around but as you work through the sections it will start to make more sense.



common extensions:

file.exe - an executable file, or program.
file.txt - a plain text file.
file.png, file.gif, file.jpg - an image.


` Linux is Case Sensitive. `


Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items. They are how we know what is the program name and can identify each command line argument. If we wanted to move into a directory called Holiday Photos for example the following would not work

 



*Quotes*


user@bash: cd 'Holiday Photos'
user@bash:pwd
/home/ryan/Documents/Holiday Photos


*Escape Characters*


user@bash: cd 'Holiday\ Photos'
user@bash:pwd
/home/ryan/Documents/Holiday Photos