su 
The Scripts switches the current user to another user, in this case betty
id
The Scripts prints the effective username of the current user
groups
prints all the groups the user is part of
chown
The scripts changes the ownership of a file from one user to another
touch
The scripts creates an empty file
chmod u+x
The Scripts adds execute permissions to the owner of a file
chmod u+x,g+x,o+r
The Scripts adds execute permissions to the owner and the group woner, and read permissions to other users.
chmod ugo+x
The Script adds execution to the owner, the group owner and the other users to a file.
chmod 007
Write a script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions. 
*or any other file that you want to do all of the above
chmod 753
The Scripts sets the mode of a file
chmod --reference
The Script sets the mode of a file to the same as another file of your specification
chmod -R ugo+X
script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
mkdir -m 751
script that creates a directory called my_dir with permissions 751 in the working directory.
chgrp
script that changes the group owner to school for the file hello
chown
Changes owner and the group owner for all files and directoies in the working directory
chown -hR
chown -h
Write a script that changes the owner and the group owner of _hello to vincent and staff respectively
chown --from=guillaume
Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
telnet towel.blinkenlights.nl
Write a script that will play the StarWars IV episode in the terminal

exit
