0-iam_betty: Switches the current user to betty.
1-who_am_i: Prints the effective username of the current user.
2-groups: Prints all groups the current user belongs to.
3-new_owner: Changes the owner of the file hello to betty.
4-empty: Creates an empty file named hello.
5-execute: Adds execute permission to the owner of the file hello.
6-multiple_permissions: Adds execute permission for the owner and group, and read permission for others, to hello.
7-everybody: Adds execute permission for all users to the file hello.
8-James_Bond: Sets hello permissions to 007, granting all permissions only to others.
9-John_Doe: Sets the permissions of hello to 753 (rwxr-x-wx).
10-mirror_permissions: Sets hello's permissions to match those of olleh.
11-directories_permissions: Adds execute permission for everyone to non-hidden immediate subdirectories without changing regular files.
12-directory_permissions: Creates my_dir with permissions 751.
13-change_group: Changes the group owner of hello to school.
14-change_owner_and_group: Changes the owner to vincent and group to staff for non-hidden files and directories in the working directory.
15-symbolic_link_permissions: Changes the owner and group of the symbolic link _hello to vincent and staff.
16-if_only: Changes the owner of hello to vincent only if its current owner is guillaume.
