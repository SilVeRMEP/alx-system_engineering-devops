Script that switches the current user to the user betty:
This script uses the su command to switch the current user to the user betty.

Script that prints the effective username of the current user:
This script uses the whoami command to print the effective username of the current user.

Script that prints all the groups the current user is part of:
This script uses the groups command to print all the groups the current user is part of.

Script that changes the owner of the file hello to the user betty:
This script uses the chown command to change the owner of the file hello to the user betty.

Script that creates an empty file called hello:
This script uses the touch command to create an empty file called hello.

Script that adds execute permission to the owner of the file hello:
This script uses the chmod command to add execute permission to the owner of the file hello.

Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello:
This script uses the chmod command to add execute permission to the owner and the group owner, and read permission to other users, to the file hello.

Script that adds execution permission to the owner, the group owner and the other users, to the file hello:
This script uses the chmod command to add execution permission to the owner, the group owner and the other users, to the file hello.

Script that sets the permission to the file hello as follows:
This script uses the chmod command to set the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions
Script that sets the mode of the file hello to a specific mode:
This script uses the chmod command to set the mode of the file hello to a specific mode (-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello).

Script that sets the mode of the file hello the same as olleh’s mode:
This script uses the chmod command to set the mode of the file hello the same as the mode of the file olleh.

Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users:
This script uses the find and chmod commands to add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

Script that creates a directory called my_dir with permissions 751 in the working directory:
This script uses the mkdir and chmod commands to create a directory called my_dir with permissions 751 in the working directory.

Script that changes the group owner to school for the file hello:
This script uses the chgrp command to change the group owner to school for the file hello.

Script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory:
This script uses the chown and chgrp commands to change the owner to vincent and the group owner to staff for all the files and directories in the working directory.

Script that changes the owner and the group owner of _hello to vincent and staff respectively:
This script uses the chown and chgrp commands to change the owner and the group owner of _hello to vincent and staff respectively. Note that _hello is a symbolic link.

This script will likely use a command-line media player, such as VLC or mplayer, to play the Star Wars IV episode in the terminal