0-iam_betty: switch user to betty using the command su betty
1-who_am_i: display the username of the current user using the command whoami
2-groups: display the groups the current user belongs to using the command groups
3-new_owner: change the owner of the file hello to betty using the command chown betty hello
4-empty: create an empty file named hello using the command touch hello
5-execute: set permissions on hello to read, write, and execute for owner, and read-only for group and others using the command chmod 744 hello
6-multiple_permissions: set permissions on hello to read, write, and execute for owner, read and execute for group, and read-only for others using the command chmod 754 hello
7-everybody: set permissions on hello to read, write, and execute for all users using the command chmod ugo+x hello
8-James_Bond: set permissions on hello to no permissions for owner and group, and read-only for others using the command chmod 007 hello
9-John_Doe: set permissions on hello to read, write, and execute for owner, read and execute for group, and write-only for others using the command chmod 753 hello
10-mirror_permissions: set the permissions of hello to match the permissions of a file named olleh using the command chmod --reference=olleh hello
11-directories_permissions: set execute permissions on all subdirectories of the current directory for the owner, group, and others using the command chmod -R ugo+X *
12-directory_permissions: create a new directory named my_dir with permissions set to read, write, and execute for owner, read and execute for group, and execute-only for others using the command mkdir -m 751 my_dir
13-change_group: change the group owner of the file hello to school using the command chgrp school hello
100-change_owner_and_group: This command uses "chown" to change the owner to "vincent" and group to "staff" for all files in the current directory. The * is a wildcard that matches all files in the directory.
101-symbolic_link_permissions: This command uses "chown" with the "-h" option to change the owner to "vincent" and group to "staff" for the symbolic link "_hello".
102-if_only: This command uses "chown" with the "--from" option to change the owner of the file "hello" from "guillaume" to "betty".
103-Star_Wars: This command uses "telnet" to connect to "towel.blinkenlights.nl", which streams the "Star Wars Episode IV: A New Hope" movie in ASCII art format in the terminal.
