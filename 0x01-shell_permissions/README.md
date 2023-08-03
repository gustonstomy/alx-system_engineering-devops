#This is the project on shell permissions
This directory contains files that will help me learn about shell basics

su betty => changes user to betty
whoami =>  prints the effective username of the current user
groups => prints all the groups the current user is part of
chown betty hello => changes the owner of the file
touch hello => creates an empty file called hello
chmod 001 hello => a script that adds execute permission to the owner of the file
chmod 001001 hello => adds user and group excution permission
chmod 001001001 hello => adds execution permission to all
chomd 007 => permission for only others
chmod 753 hello => permission -rwxr-x-wx 
chmod 664 hello => permission as elloh
chmod -R +x => permission to all subdirectories of the current directory for the owner
mkdir -m 751 my-dir => creates a directory called my-dir with permissions 751 in the working directory.
chgrp school hello => changes the group owner to school for the file hello
chown vincent:staff * => changes the owner to vincent and the group owner to staff for all the files and directories
chown -h vincent:staff _hello => changes the owner and the group owner of _hello to vincent and staff respectively
