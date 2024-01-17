# CSE15L Lab Report 1
## Breanna Huynh
## January 15, 2024
## CSE 15L


## command 1. cd
1. No argument
![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/67cfd5c7-a4f0-4e34-b1a4-9e67240d7914)

* When the command was ran, the working directory is "/home".
* The command was ran without any arguments, resulting in an output of nothing. The working directory is still "/home" since there was no argument that the current working directory would switch to.  
* Because the output printed nothing, this means that it finished with no errors.

2. *Directory* as argument
   
![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/c737c5a4-e07f-4db6-a703-6e5be09287f3)

* When the command was ran, the working directory is "/home"
* In this case, lecture1 is the given path that is being switched to. After the command was ran, there was no output, however there was now a "/lecture1" next to the user which signified that the current working directory is now in lecture1.
* The output is not an error.

3. *File* as argument
   
![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/084f6d0f-4d56-4e1c-a4e6-75b135965750)


* When the command was ran, the working directory is still "/home/lecture1"
* After running the command, the output was "bash:  cd:  Hello.class: Not a directory". Hello.class is a file and not a directory, therefore the command was unable to switch the current working directory to Hello.class. 
* The output is an error. The cd command only takes in directories as an argument and because Hello.class is a file, the output printed out an error messages stating that Hello.class is not a directory. 

## command 2. ls
1. No argument

![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/4e76f4d4-b02a-4680-98dc-9d5e54ca3ef1)

* When the command was ran, the working directory is "/home"
* The command outputted "lecture1" after the command was ran with no argument. The working directory is "/home", so by running the command the output listed the current files and folders in home.
* The output is not an error.

2. *Directory* as argument

![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/00d36280-6a71-468d-b384-63d834135e20)

* When the command was ran, the working directory is "/home"
* After the command was ran, the output was "Hello.class  Hello.java  **messages**  README". The command listed the current files and folders in the given path, lecture1. 
* The output is not an error

3. *File* as argument

![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/a6e0f8d8-261e-4bd8-b547-b073793fc157)

* When the command was ran, the working directory is "/home/lecture1"
* The output is "Hello.java". The command listed the files and folders in the given path, which is Hello.java
* The output is not an error.

  ## command 3. cat
1. No argument

![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/beb06d34-9ce8-47e0-b18a-b7b7289b6bd3)

* When the command was ran, the working directory is "/home"
* Because there were no arguments, the command read from the terminal, resulting in a blank line as the output. By typing in the blank space, the following line outputs the entered text.
* This is not an error, by running cat without any arguments, it begins to concatenate text that is in the terminal. There is no error message displayed as well.

2. *Directory* as argument

![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/6e803e29-d11e-4cbf-a1e3-8c721272c958)

* When the command was ran, the working directory is "/home"
* The output prints out "cat: lecture1: Is a directory" for both lines. Because lecture1 is a directory, it cannot be concatenated. 
* This is an error as the cat command is only used with file contents. Lecture1 is not a file, thus the output prints an error messages stating that lecture1 is a directory. 

3. *File* as argument

![image](https://github.com/beeannah/cse15l-lab-reports/assets/156740070/18ea2a5e-8da3-498a-ba86-b0a98da36a6b)

* When the command was ran, the working directory is "/home/lecture1/messages"
* The output is "Hello World!" followed by a line that prints "¡Hola Mundo!". The command concatenated and printed the contents of en-us.txt and es-mx.txt.
* The output is not an error.

