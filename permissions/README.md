NOTE: Ways to solve possible problems: 
   -> always make file exetutable (chmod u+x)
   -> make sure you have a README.md in the directory which is not empty (just like this README.md)
   -> dont forget to add "shebang" (#!/bin/bash) to every file

0: script that switches the current user to the user betty.            >>>command: su <username>
1: script that prints the effective username of the current user.      >>>command: whoami
2: script that prints all the groups the current user is part of.      >>>command: groups <username>
3: script that changes the owner of the file hello to the user betty.  >>>command: chown <username> file_name    !NOTE!: you should create file hello first
4: just command to create file "hello" .                               >>>command: touch file_name
5. give permission to execute file "hello".                            >>>command: chmod <permission> file_name
6. give permission to owner of file and group owner to execute "hello" >>>command: chmod <permission> file_name
