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
