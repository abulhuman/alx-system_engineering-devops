# 0x01-Shell Permissions
1. `0-iam_betty` - changes current user to `betty`. 
1. `1-who_am_i` - prints current user.
1. `2-groups` - prints all the groups of the current user.
1. `3-new_owner` - changes owner of `hello` file to `betty`.
1. `4-empty` - creates an empty file called `hello`.
1. `5-execute` - adds execute permission to `./hello` file.
1. `6-multiple_permissions` - adds execute permission to the owner and the group owner, and read permission to other users to the `./hello` file.
1. `7-everybody` - adds execution permission to the owner, the group owner and the other users, to the `./hello` file.
1. `8-James_Bond` - sets the following permissions on `./hello` file:
   > - Owner: no permission.
   > - Group: no permission.
   > - Other users: all permissions.
1. `9-John_Doe` - sets the mode of `./hello` file to `-rwxr-x-wx`.
1. `10-mirror_permissions` - sets the mode of `./hello` to the mode of `./olleh`.
1. `11-directories_permissions` - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files will not be changed.
1. `12-directory_permissions` - creates a directory called my_dir with permissions 751 in the working directory.
1. `13-change_group` - changes the group owner to `./school` for the `./hello` file.
