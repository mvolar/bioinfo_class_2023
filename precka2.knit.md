---
title: "Terminal basics"
author: "Marin Volarić"
date: "2023-01-11"
output:  
  beamer_presentation:
      theme: "AnnArbor"
      colortheme: "dolphin"
      fonttheme: "structurebold"
---

## Linux terminal

What even is a "terminal" or "console"?

![](terminal.png)

## Why would you use it?

-   speed
-   once learned it is 1000x more efficient than using explorer
-   best and newest programs don't have a GUI
-   one you get a hang of it you can do crazy things

# But first...

## Basic movement

File path notation

```bash
path/ # ====> search in this foldewr 
./file.txt # ===> current directory prefix (./)
~/... # ===> from user Home (where we have desktop,downloads,etc)
/... # ===> most dangerous, goes from home root

```

Going into directories

```bash
#to enter a folder
cd dirname
#to go to the parent folder 
cd ..
```

## Create or remove a directory




```bash
#to create a directory
mkdir dirname
#remove any directory
rm -r dirname
#also remove a file
rm file
```

## Basic commands


```bash

#display top 10 lines of a file
head
#bottom 10 lines of a file
tail
#copy one file to another
cp path/to/file1.txt path/to/copy.txt 
#move from file to file, also rename
mv path/to/file1.txt path/to/move.txt 
#touch a file
touch file.txt
```

## Exercise 1

Create a new directory on your Desktop, called whatever, and 
