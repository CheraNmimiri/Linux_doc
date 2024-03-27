### Creating and Managing Users

#### Adding Users to Linux
- To add users to Linux: `useradd [username]`

#### Adding Groups to Linux
- To add groups to Linux: `groupadd [group-name]`

#### Changing User's Password
- To change a user's password: `passwd [username]`

#### Showing Recently Logged Users (Auditing)
- To show recently logged users: `last`

#### Modifying User Properties
- To modify user properties, such as adding user to a group: `usermod -a -G [group-name] [username]`

#### Deleting a User
- To delete a user and their home directory: `userdel -r [username]`

#### Deleting a Group
- To delete a group: `groupdel [group-name]`

### Access Files and Ownership

#### Access Permissions
- Access permissions have 10 parts:
  - Part 1: File or directory (f or d)
  - Parts 2-4: Users access, group access, others access (read=4, write=2, execute=1)
  - Execute in directory allows `cd` into it.

#### Changing Permissions
- To change permissions: `chmod`
- Full control permission: `chmod 777 [file-name]`
- No permissions: `chmod 000 [file-name]`
- Full control a directory and subfiles or subdirectories: `chmod 777 [dir-name] -R`

#### Changing Ownership
- To change ownership: `chown [user-name] [file-or-dir-name]`
- To change ownership of directory and its subfiles and subdirectories: `chown [user-name] [file-or-dir-name] -R`

#### Changing Group
- To change group: `chgrp [group-name] [file-or-dir-name]`
  - Can use `-R` switch for recursive change.
