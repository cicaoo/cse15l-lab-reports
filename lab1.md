# Lab Report #1: Remote Access and FileSystem (Week 1)
## Cindy Cao
Lecture: Mondays and Wednesdays | 9:00-9:50 <br>
Lab: Wednesdays | 2:00-3:50 <br> <br>

COMMANDS <br>
1) **cd** <br> 
```
[user@sahara ~/lecture1]$ cd
[user@sahara ~]$
```
- When the command "cd" was ran, the working directory was /home/lecture1. <br>
- Running the command "cd" without an argument switched the working directory to the root directory. <br>
- This output is not an error. <br> <br>
  
```
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$
```
- When the command "cd" was ran, the working directory was /home. <br>
- Running the command "cd" with an argument of lecture1 (which is a directory) switched the working directory to lecture1. <br>  
- This output is not an error. <br> <br>
  
```
[user@sahara ~/lecture1]$ cd lecture1/Hello.java
bash: cd: lecture1/Hello.java: No such file or directory
[user@sahara ~/lecture1]$
```
- When the command "cd" was ran, the working directory was /home/lecture1. <br>
- Running the command "cd" with a path to the file lecture1 did not switch the working directory, and it remained at lecture1. <br>
- This output is an error because the command "cd" cannot be used to switch a directory to a file. When "cd" is combined with an argument of a file but not a directory, the directory cannot be switched and that is why an error occurs. <br> <br>
2) **ls** <br>
```
[user@sahara ~/lecture1]$ ls
Hello.class  Hello.java  messages  README
[user@sahara ~/lecture1]$
```
- When the command "ls" was ran, the working directory was /home/lecture1. <br>
- Running the command "ls" without any arguments lists out the folders and files in the given directory. In this case, "ls" lists out the files and folders in /home/lecture1.
- This output is not an error. <br> <br>
```
[user@sahara ~/lecture1]$ ls messages
ar-lb.txt  en-us.txt  es-mx.txt  zh-cn.txt
[user@sahara ~/lecture1]$ 
```
- When the command "ls" was ran, the working directory was /home/lecture1/. <br>
- Running the command "ls" with a path to the directory messages lists the 

