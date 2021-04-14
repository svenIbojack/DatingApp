# How to setup Version Control with the command-line interface 

## Initialize Version Control

First of all you have to select a folder where you want to store your code. 
In my example case that would be the folder Development. Obviously a folder with this name stores multiple projects. Thats why we have to create a new folder with our project name.

```
C:\Development> mkdir EnglischDemo
```

Now we have the folder for our project but we will not be able to use git  commands. Thats right, every command that we need for the version control starts with "git". We have to switch into our project folder and give him the command to initalize git. After that our project folder is our new repository for our project.

```
C:\Development> cd EnglischDemo
C:\Development\EnglischDemo> git init
Initialized empty Git repository in C:\Development\EnglischDemo/.git/
```
After that step you can find in our repository a .git folder (secret folder) and a Readme.md. More information about that you can find on ...Link...

## The basic commands