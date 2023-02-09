# ALX System Engineering Devops :computer:
## Description
#### ALX's curriculum for software engineering is specifically aimed at projects which are meant to help you learn what it takes to become great Software Engineers.

1. ## [0x00. Shell, basics](https://github.com/abrahamdominic/alx-system_engineering-devops/tree/main/0x00-shell_basics)

2. ## [0x00. Shell, permissions](https://github.com/abrahamdominic/alx-system_engineering-devops/tree/main/0x01-shell_permissions)

3. ## [0x00. Shell,I/O Redirections and Filters ](https://github.com/abrahamdominic/alx-system_engineering-devops/tree/main/0x02-shell_redirections)

4. ## [0x00. Shell, init files, variables and expansions](https://github.com/abrahamdominic/alx-system_engineering-devops/tree/main/0x03-shell_variables_expansions)

# How to solve Shell Basic task

# SHELL BASICS

Y'all know how to create a repository and clone.
So you'll create this repository alx-system_engineering-devops on GitHub
Then in your sandbox webterminal you type 

git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-system_engineering-devops.git                  

Replace {YOUR_PERSONAL_TOKEN} with your personal access token from GitHub 

Replace {YOUR_USERNAME} with your GitHub username 

You  will see 

Cloning into 'alx-system_engineering-devops'...
warning: You appear to have cloned an empty repository.

# Next type 

cd alx-system_engineering-devops

touch README.md

echo ‘This repository contains solutions to shell tasks’ > README.md

mkdir 0x00-shell_basics

cd 0x00-shell_basics

touch README.md

echo ‘(please put your own words here)’ > README.md

git add .

git commit -m “(please put your own words here)”

git push

# TASK 0
make sure you are in alx-system_engineering-devops repository 

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics   Enter

touch 0-current_working_directory      Enter

vi 0-current_working_directory               Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

pwd

After click ESC and type :wq            Enter

chmod u+x 0-current_working_directory        Enter 

cd ..                          Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 1

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics             Enter

touch 1-listit       Enter

vi 1-listit              Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

ls

After click ESC and type :wq            Enter

chmod u+x 1-listit      Enter 

cd ..                          Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 2

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics             Enter

touch 2-bring_me_home       Enter

vi 2-bring_me_home               Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

cd ~ 

After click ESC and type :wq            Enter

chmod u+x 2-bring_me_home        Enter 

cd ..                          Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 3
make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics

touch 3-listfiles 

vi 3-listfiles

(press i for insert mode then type the two lines below)

#!/bin/bash

ls -l

After click ESC and type :wq            Enter

chmod u+x 3-listfiles                         Enter 

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push

# Task 4

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics

touch 4-listmorefiles 

vi 4-listmorefiles

(press i for insert mode then type the two lines below)

#!/bin/bash

ls -la

After click ESC and type :wq            Enter

chmod u+x 4-listmorefiles                Enter 

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 5

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics

touch 5-listfilesdigitonly

vi 5-listfilesdigitonly

(press i for insert mode then type the two lines below)

#!/bin/bash

ls -na

After click ESC and type :wq            Enter

chmod u+x 5-listfilesdigitonly           Enter 

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 6

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics

touch 6-firstdirectory 

vi 6-firstdirectory

(press i for insert mode then type the two lines below)

#!/bin/bash

mkdir /tmp/my_first_directory

After click ESC and type :wq            Enter

chmod u+x 6-firstdirectory                Enter 

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 7

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics             Enter

touch 7-move that file            Enter 

vi 7-movethatfile                     Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

mv /tmp/betty /tmp/my_first_directory 

After click ESC and type :wq            Enter

chmod u+x 7-movethatfile 
cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 8

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics.              Enter

touch 8-firstdelete                    Enter

vi 8-firstdelete                           Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

rm /tmp/my_first_directory/betty

After click ESC and type :wq           Enter

chmod u+x 8-firstdelete                Enter

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 9

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics           Enter 

touch 9-firstdirdeletion             Enter

vi 9-firstdirdeletion                    Enter 

(press i for insert mode then type the two lines below)

#!/bin/bash

rm -rf /tmp/my_first_directory/


After click ESC and type :wq           Enter

chmod u+x 9-firstdirdeletion           Enter

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push

#TASK 10

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics             Enter

touch 10-back                         Enter

Vi 10-back                                Enter 

(press i for insert mode then type the two lines below)

#!/bin/bash

cd -

After click ESC and type :wq           Enter

chmod u+x 10-back                         Enter

cd ..                                                    Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 11

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics             Enter

touch 11-lists                            Enter

vi 11-lists                                   Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

ls -la . .. /boot

After click ESC and type :wq           Enter

chmod u+x 11-lists                          Enter

cd ..                                                   Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 12

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics               Enter

touch 12-file_type                     Enter

vi 12-file_type                            Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

file /tmp/iamafile

After click ESC and type :wq           Enter

chmod u+x 12-file_type                    Enter

cd ..                                               Enter

git add .

git commit -m "(please put your own message)

git push

# TASK 13

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics                 Enter

touch 13-symbolic_link              Enter

vi 13-symbolic_link                     Enter 

(press i for insert mode then type the two lines below)

#!/bin/bash

ln -s /bin/ls  __ls__

After click ESC and type :wq           Enter

chmod u+x 13-symbolic_link           Enter

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push 

# TASK 14

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics               Enter

touch 14-copy_html                  Enter

vi 14-copy_html                         Enter 

(press i for insert mode then type the two lines below)

#!/bin/bash

cp -un *.html ../

After click ESC and type :wq           Enter

chmod u+x 14-copy_html                Enter

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push 

So for the bonus tasks

# TASK 15

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics               Enter

touch 100-lets_move                Enter

vi 100-lets_move                       Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

mv [[:upper:]]* /tmp/u

After click ESC and type :wq           Enter

chmod u+x 100-lets_move              Enter

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push 

# TASK 16

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics               Enter

touch 101-clean_emacs           Enter

vi 101-clean_emacs                  Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

rm *~

After click ESC and type :wq           Enter

chmod u+x 101-clean_emacs          Enter

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push 

# TASK 17

make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics               Enter

touch 102-tree                           Enter

vi 102-tree                                  Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

mkdir -p welcome/to/school

After click ESC and type :wq           Enter

chmod u+x 102-tree                         Enter

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push 


# TASK 18
make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics               Enter

touch 103-commas                   Enter

vi 103-commas                          Enter

(press i for insert mode then type the two lines below)

#!/bin/bash

ls -amp | sort -d

After click ESC and type :wq           Enter

chmod u+x 103-commas                 Enter

cd ..                             Enter
git add .

git commit -m "(please put your own message)

git push 

# Task 19
make sure you are in alx-system_engineering-devops

If you are not type cd alx-system_engineering-devops

cd 0x00-shell_basics               Enter

touch school.mgc                     Enter

vi school.mgc                            Enter

(press i for insert mode then type the three lines below)

#!/bin/bash

0 string SCHOOL School data

!:mime School

After click ESC and type :wq            Enter

file -C -m school.mgc                       Enter

chmod u+x school.mgc                    Enter

cd ..                             Enter

git add .

git commit -m "(please put your own message)

git push
