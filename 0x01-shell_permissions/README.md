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
