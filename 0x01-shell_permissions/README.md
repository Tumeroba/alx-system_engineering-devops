sudo login betty to change current user to betty
whoami prints the effective username of the current use
groups prints all groups that current user is part of 
sudo chown betty hello changes the own of file hellow to betty
touch creates and empty file
chmod u+x hello adds excussion permission to the own of the file
chmod 754 gives owner pemission to read write and exercute group to read and exercute and others to read
chmod ugo+x hello gives owner read, write and exercute permisson and exercute permission to groups and other users
chmod 007 gives no right to owner and group. And all permission to other users 
chmod 753 gives this permissions -rwxr-x-wx
chmod --reference=olleh hello set the mode of hello same as olleh's
chmod ugo+x ./* adds execution permission to all subdirectories of current directory, to owner group and other users
mkdir -m 751 my-dir will create a directory with 751 permission in working directory
chgrp school hello  changes the group owner of hello file to school 
