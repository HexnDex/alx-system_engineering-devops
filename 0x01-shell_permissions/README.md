Task 0. su betty - Change current user to betty
Task 1. whoami -prints the effective username of the current user
Task 2. groups - prints all the groups the current user is part of
Task 3. chown betty hello - changes the owner of the file hello to the user betty.
Task 4. touch hello - creates empty file hello
Task 5. chmod u+x hello - gives owner of file excution permission
Task 6. chmod 554 hello - execute permission to owner, ownergroup and read to all others
Task 7. chmod a+x hello - execute permission to all
Task 8. chmod 007 hello - all permissions to only others and no permission to owner and owner groups
Task 9. chmod 753 hello - all permission for owner, read and ex for group and write and ex for all others
Task 10. chmod --reference=olleh hello -  a script that sets the mode of the file hello the same as olleh’s mode.
Task 11. chmod -R ugo+X * - script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
Task 12. mkdir my_dir -m=751 -  a script that creates a directory called my_dir with permissions 751 in the working directory.
Task 13. chgrp school hello - a script that changes the group owner to school for the file hello
Task 14. chown vincent:staff *  - a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
Task 15. chown -h vincent:staff _hello - a script that changes the owner and the group owner of _hello to vincent and staff respectively.
Task 16. chown --from=guillaume betty hello - a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
Task 17. telnet towel.blinkenlights.nl - a script that will play the StarWars IV episode in the terminal.
