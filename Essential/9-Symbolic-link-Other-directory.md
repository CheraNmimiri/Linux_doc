### Symbolic Links and Specific Directories

#### Symbolic Link
- Symbolic link acts as a shortcut or pointer to another file or directory.
- Create a symbolic link: `ln -s [file-or-dir-name] [linked-file]`

#### Specific Directories

##### /tmp
- Short-term storage or temporary storage (like RAM where files are deleted upon system restart).

##### /var/tmp
- Similar to `/tmp` but persistent.

##### /var/
- Contains files that are often changed, such as databases, mail, and logs.

#### Sticky Bit
- The sticky bit ensures that only the owner of a file or directory can delete or rename it, even if other users have write permissions.
- Apply sticky bit: `chmod +t [dir-name]`
