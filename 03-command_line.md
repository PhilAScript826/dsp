# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > pwd, mkdir "directory", rmdir "directory", touch "file name", rm "file name", mv "file name" "new name", ls -a, cp "file" "directory", cat "file" prints the contents of the file, ls -l "path" prints the persmission of the file listed.

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > ls = "list the directories and files in the current working directory"
ls -a = "list the hidden directories and files in the working directory"
ls -l = "list the permissions of all directories and files in the working directory"
ls -lh = "list the permissions of all directories and files in the working directory in human readable format"
ls -lah = "list the permissions of all hidden directories and files in root use and working directory in human reable format"
ls -t = "list the directories and files in the working directory by modification time"
ls -Glp = "list all directories and files with CLICOLOR, / if it is a directory, and it's permissions in the working directory"

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > -p, -R, -a, -1,-G 

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > It takes arguments to the left of it and executes it with an optional command. It is good to do multiple task at once or to make changes to several items in a directory. 
Example: ls | xargs rm = " removes all the files in the current working directory"

 

