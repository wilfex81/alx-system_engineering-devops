<<<<<<< HEAD
#!/bin/bash
"pwd" This command prints the current working directory
cd
Changes directory to the previous one
ls -al . .. /boot
lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile
 prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
ln -s /bin/ls __ls__
Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
cp -nu *.html ..
copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
=======
pwd
This prints the current working directory
ls
Displays the list of the current directory
cd
Changes the working directory to user's home directory
ls -l
Displays contents of the current directory in long
ls -la ..
displays contents of the current directory including hidden files in tthe long formt
ls -la ..
Display current directory contents.

Long format
with user and group IDs displayed numerically
And hidden files (starting with .)
touch 
creates a directory 
*sorry, mkdir creates a directory
mv
moves files from one directory to another
rm
deletes a file
rm -r 
deletes a directory
>>>>>>> 0ef12bae9b5f8f3c8beb675e618e27d13e9b3013
mv [[:upper:]]* /tmp/u
t moves all files beginning with an uppercase letter to the directory /tmp/u.

You can assume that the directory /tmp/u will exist when we will run your script
rm *~
deletes all files in the current working directory that end with the character ~.
mkdir -p welcome/to/school
Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
ls -pamv
Write a command that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line
