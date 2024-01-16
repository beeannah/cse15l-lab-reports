# CSE15L Lab Report 1
## Breanna Huynh
## January 15, 2024
## CSE 15L

// each command: cd, ls, cat 

## command 1. cd
1. No argument
![Image](cd no argument.png)
* When the command was ran, the working directory is "/home".
* The command was ran without any arguments, resulting in an output of nothing. The working directory is still "/home" since there was no argument that the current working directory would switch to.  
* Because the output printed nothing, this means that it finished with no errors.

2. *Directory* as argument
//insert image
* When the command was ran, the working directory is now "/home/lecture1"
* In this case, lecture1 is the given path that is being switched to. After the command was ran, there was no output, however there was now a "/lecture1" next to the user which signified that the current working directory is now in lecture1.
* The output is not an error.

3. *File* as argument
//insert image
* When the command was ran, the working directoryt is still "/home/lecture1"
* After running the command, the output was "bash:  cd:  Hello.class: Not a directory". Hello.class is a file and not a directory, therefore the command was unable to switch the current working directory to Hello.class. 
* The output is an error. The cd command only takes in directories as an argument and because Hello.class is a file, the output printed out an error messages stating that Hello.class is not a directory. 

## command 2. ls
1. No argument
//insert image
* 
