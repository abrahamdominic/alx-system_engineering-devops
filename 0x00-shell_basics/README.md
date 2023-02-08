# Welcome to 0x00-shell\_basics
## Description
#### This project explores the fundamentals of the shell; navigating the shell environment.
## Learning Objectives
#### Students at the end of this module are expected to have learned and understood:
- What a shell is.
- The difference between a terminal and a shell
- What is the shell prompt
- How to use the history(the basics)
- What do the commands or built-ins `cd`,`pwd`,`ls` do
- How to navigate the file system
- What are the `.` and `..` directories
- What is the working directory, how to print it and how to change it
- What is the home directory and how to go there
- The difference between the root directory and the home directory of the user root
- What are the characteristics of hidden files and how to list them
- What does the `cd` command do.
- Understand the ls long format and how to display it.
- What is a symbolic link
- What is a hard link
- The difference between a hard link and a symbolic link.
- Functions of the `cp`, `mv`, `rm`, and `mkdir` commands
- When to use the help command instead of man command
- What is an alias

### 0-current_working_directory
- This script prints the absolute path name of the current working directory

### 1-listit
- This script displays the contents list of your current directory

### 2-bring_me_home
- This script changes the current working directory to the user's home directory

### 3-listfiles
- This script displays the content of the current directory in a long format

### 4-listmorefiles
- This list displays the content of the current working directory including hidden files in a long format.

### 5-listfilesdigitonly
- This script displays the content of the current directory along with both user and group IDs and hidden files.

### 6-firstdirectory
- This script creates a directory named `my_first_directory` in the `/tmp/` directory.

### 7-movethatfile
- This script moves the `betty` file from `/tmp/` to `/tmp/my_first_directory`.

### 8-firstdelete
- This script deletes the file `betty` from the `/tmp/my_first_directory`

### 9-firstdirdeletion
- This script deletes the directory `my_first_directory` in the `/tmp` directory.

### 10-back
- This script changes the directory to the previous one.

### 11-lists
- This script list all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory(in this order), in long format.

### 12-file_type
- This script prints the type of the file named `iamafile`. The file will be in the `/tmp` directory when the script is run.

### 13-symbolic_link
- This script creates a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current workinv directory.

### 14-copy_html
- This script copies all the HTML files from the current directory to the parent directory, but only copies files that does not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

### 100-let's_move
- This script moves all files beginning with an uppercase letter to the directory `/tmp/u`

### 101-cleam_emacs
- This script deletes all the files in the current working directory that ends with `~`.

### 102-tree
- This script creates the directories `welcome/`, `welcome/to` and `welcome/to/school` in the current working directory. **Note:** It is only allowed to use two spaces (and lines) in the script and not more!

### 103-commas
- This script lists all the files and directories in the current directory, separated by commas (`,`)

### school.mgc
- This is a creation of a magic file that can be used with the `file` command to detect `School` data files. `School` data files always contain the string `SCHOOL` at offset 0.
