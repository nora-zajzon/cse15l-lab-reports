_Hello_

Nora Zajzon's Lab #1
=========
Here is the link to my github [profile](https://github.com/nora-zajzon)

This is my Dog Cherry
---------
![Image](cherry.jpeg)
> I have two dogs but I wanted to use this picture

Classes I am taking this quarter:
---
* CSE 15L
* CSE 20
* CSE 12
* HILD 7B
* MCWP 50
* Independent Research
  
`Units:` 19 total

```
This is the end of the rambling to prove I can use different syntax
Next are my answers to the lab questions
```

No Arguments
=========
![Image](NoArgs.png)

1) `cd` The output of this command line was expected as no directory was selected. Therefore, when cd is used and no argument is given, no change in directory will be made. This is not an error. __Current Directory when command was run: /home__
2) `ls` The output of this command line was expected to return the files and directories in the current directory. Since the current directory is /home, it will only list lecture1 since it is the only directory or file in /home. This is not an error. __Current Directory when command was run: /home__
3) `cat` The output of this command line was expected since no file was given as an argument. The cat command with no args like many UNIX commands is reading from the standard input. This is an error in the sense that the command can not terminate so the terminal can not return to the command line. It is not necessarily an error but rather waits for input from the user through the standard input. __Current Directory when command was run: /home__

Command with a path to a directory as an argument
=========
![Image](Directory.png)

1) `cd lecture1/` The output of this command line was expected as the directory lecture1 was as an argument. Therefore, the current directory will be changed to the lecture1 directory. This is not an error. __Current Directory when command was run: /home__
2) `ls lecture1/` The output of this command line was expected to return the files and directories in the current directory. Since the current directory is /home/lecture1, it will list all of the files and directories within lecture1. This is not an error. __Current Directory when command was run: /home__
3) `cat lecture1/` The output of this command line was expected since no file was given as an argument. Since a directory is given instead of a file, the terminal will automatically state that the argument given is a directory. This is an error in the sense the command of cat is not carried through since it can not print the content of a file. In order to have an output to a directory that does not return an error, the command line would need to be cat lecture1/*.txt. __Current Directory when command was run: /home__

Command with a path to a file as an argument
=========
![Image](Files.png)

1) `cd en-us.txt` The output of this command line was expected as the file en-us.txt was as the argument. Therefore, the current directory cannot change to a file and will remain the same. This is an error in the sense that the current directory is not changed to the file given as an argument. __Current Directory when command was run: /home/lecture1/messsages__
2) `ls en-us.txt` The output of this command line was expected was expected to display information about the file 'en-us.txt' in the current directory. If you give a file name as an argument, it will display information about that one single file, so if the argument is a directory or empty, then it will display information about the files in that folder or information about one file if it is one file. This is an error in the sense that nothing will be listed as a result of the command other than the file you are in. __Current Directory when command was run: /home/lecture1/messsages__
3) `cat en-us.txt` The output of this command line was expected a file was given as an argument in the command. The terminal will print the content of the file. This is not an error. __Current Directory when command was run: /home/lecture1/messsages__
