## Objetive 

The password for the next level is stored in a file called - located in the home directory

## What is discontinued filename ?
This refers to a file that contains a hyphen or a number. This can cause problems when creating files on Unix and macOS operating systems.


## Solution 
1-Check which directory I'm in.
2-Verify that the file is in the current directory.
3-Verify if I can read it with cat.
4-Use cat ./-  to indicate that it should start reading the file by its relative path, preventing the shell from reading it as the first character.
This will give us the password 263JGJPfgU6LtdEvgfWU1XP5yac29mFx 
## commands used
ssh 
pwd
ls 
cat 
cat ./-
