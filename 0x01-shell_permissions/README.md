su betty - Creates a script that switches the current user to the user betty. You should use exactly 8 characters for your command (+1 character for the new line). You can assume that the user betty will exist when we will run your script
whoami - Prints the effective username of the current user
groups - Prints all the groups the current user is part of
sudo chown betty hello - Changes the owner of the file hello to the user betty
touch hello - Creates an empty file called hello
chmod u+x hello - Adds execute permission to the owner of the file hello
chmod +114 hello - Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. The file hello will be in the working directory
chmod +111 hello - Adds execution permission to the owner, the group owner and the other users, to the file hello. The file hello will be in the working directory. You are not allowed to use commas for this script
chmod 007 hello - Sets the permission to the file hello as follows: Owner: no permission at all, Group: no permission at all and Other users: all the permissions. The file hello will be in the working directory You are not allowed to use commas for this script
chmod 753 hello - Sets the mode of the file hello as follows: The file hello will be in the working directory and you are not allowed to use commas for this script
chmod --reference olleh hello - Sets the mode of the file hello the same as olleh’s mode. The file hello will be in the working directory and the file olleh will be in the working directory
chmod a+x */ - Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed
mkdir -m 751 my_dir - Creates a directory called my_dir with permissions 751 in the working directory
chgrp school hello - Changes the group owner to school for the file hello. The file hello will be in the working directory
chown -h vincent:staff _hello - Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
chown --from=guillaume betty hello - Changes the owner and the group owner of _hello to vincent and staff respectively. The file _hello is in the working directory and the file _hello is a symbolic link
telnet towel.blinkenlights.nl - Changes the owner of the file hello to betty only if it is owned by the user guillaume. The file hello will be in the working directory
