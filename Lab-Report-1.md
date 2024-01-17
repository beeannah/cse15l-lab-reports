# CSE15L Lab Report 1
## Breanna Huynh
## January 15, 2024
## CSE 15L

// each command: cd, ls, cat 

## command 1. cd
1. No argument
![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/67cfd5c7-a4f0-4e34-b1a4-9e67240d7914)

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
* When the command was ran, the working directory is still "/home/lecture1"
* After running the command, the output was "bash:  cd:  Hello.class: Not a directory". Hello.class is a file and not a directory, therefore the command was unable to switch the current working directory to Hello.class. 
* The output is an error. The cd command only takes in directories as an argument and because Hello.class is a file, the output printed out an error messages stating that Hello.class is not a directory. 

## command 2. ls
1. No argument
//insert image
* When the command was ran, the working directory is "/home"
* The command outputted "lecture1" after the command was ran with no argument. The working directory is "/home", so by running the command the output listed the current files and folders in home.
* The output is not an error.

2. *Directory* as argument
//insert image
* When the command was ran, the working directory is "/home"
* After the command was ran, the output was ""Hello.class  Hello.java  **messages**  README". The command listed the current files and folders in the given path, lecture1. 
* The output is not an error

// **CHECK IF CORRECT** 3. *File* as argument
* When the command was ran, the working directory is "/home"
* The output is "ls:  cannot acces 'Hello.java': No such file or directory". There are no files or folders in "Hello.java", prompting the output to print out an error message.
* The output is an error because there are no files or folders in "Hello.java". The ls command is used to access and list  the current files and folders in the given path.

  ## command 3. cat
//insert image
1. No argument
* When the command was ran, the working directory is "/home"
* Because there were no arguments, the command read from the terminal, resulting in a blank line as the output. By typing in the blank space, the following line outputs the entered text.
* This is not an error, by running cat without any arguments, it begins to concatenate text that is in the terminal. There is no error message displayed as well.

2. *Directory* as argument
//insert image
* When the command was ran, the working directory is "home/lecture1/messages"
* The output read "cat:  lecture1: No such file or directory" for both lines. The command cat only displays contents of files and do not work for directories such as lecture1.
* The output is an error. Cat is used to print the contents of files, not directories. Because lecture1 was used as the argument, an error was outputted as cat does not concatenate directories. 

3. *File* as argument
//insert image
* When the command was ran, the working directory is "/home/lecture1/messages"
* The output is "Hello World!" followed by a line that prints "¡Hola Mundo!". The command concatenated and printed the contents of en-us.txt and es-mx.txt.
* The output is not an error.

