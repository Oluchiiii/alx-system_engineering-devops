Starting to try out change user commands and other permission commands
Switching user to betty: su betty
Printing effective username of current user: id -un
Printing all the groups that the current user is part of: id -Gn
Changing user of file: sudo chown betty hello
Writing a script to create an empty file: touch hello
Adding execute permission:  chmod u+x hello
Adding multiple permissions: chmod ug+x,o+r hello
Adding execute permission to everybody: chmod ugo+x hello
No permission for user/group:all permissions for group: chmod 007 hello
Setting modes offhand: chmod 753 hello
Directories Permissions: chmod a+X *
Mirror permissions: chmod --reference=olleh hello
Making directories with permissions attached: mkdir -m751 my_dir
Changing group owner: chgrp school hello
Changing owner and group: chown vincent:staff *
Changing symbolic link owner and group owner: sudo chown -h vincent:staff _hello
Changing owner if_only: sudo chown --from=guillaume betty hello
