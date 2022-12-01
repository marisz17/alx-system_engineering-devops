**Description of what each script does in 0x00-shell_permissions**
0-iam_betty - switches current user to user betty.
1-who_am_i - prints effective username of the current user.
2-groups - prints all groups user is part of.
3-new_owner - changes owner of file 'hello' to user: betty.
4-empty - creates an empty file named hello.
5-execute -add x permission to owner.
6-multiple_permissions - adds x permission to owner and group owner and r permission to others to the file hello.
7-everybody - gives x permission everyone.
8-James_bond - sets permissions, none for owner, none for group, all for others.
9-John_Doe -change permissions to -rwxr-x-wx.
10-mirror-permissions - mirror permissions of olleh to hello
11-directories_permissions - adds x permission to subdirs not files to owner,group and others.
12-directory_permissions - create dir with permission 751 octal.
13-change_group - change group owner of hello to school.