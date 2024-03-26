## Linux commands

change user password : 'passwd [user]'
show list of file and directory : 'ls'; 
show permissions use : "ls -l"
show all even hide file : 'ls -a'
recursive view or show all and whole details of file directory : 'ls -R'
clear terminal : 'clear'
symbol of home directory : '~'
show details files : 'cat [file-name]'
print text : 'echo ['text']'
symbol used for call variable : '$'; exp:a=5, echo $a
symbol for command : ';'
globbing : just show files with specify suffix; exp:ls *.txt=> everything is txt, ls file??.txt => everything start with file and have 2 another char and is txt
watch command like variable enviroment in windows : echo $PATH
show path of terminal command : 'whereis [command-name]'
show your path now : 'pwd'
show manual of every command : 'man [command-name]'
update manual and add new manual : 'sudo mandb'
search a key on all manual context : 'man -k [key-name]'
show manual with simple : 'info [command-name]'
a brif description about command : 'whatis [command-name]'
show detail of zip file : 'less [name file]'
access to all document : /usr/share/doc

**Tip**: with use cd command without anything, you comming back to home directory

craete empty file or update last access time, file with name and no content : 'touch [file-name]'
by defualt only removes files but can also remove folders : 'rm [file-or-directory-name]'
moves files and folders, **also renames files and folders** : 'mv [file-or-directory-name]' [destination], rename : mv [filename] [newfilename]
by default only renames files : 'cp [filename] [des-path]'
copy directory to directory : cp -R [dir_name] [destination-dir]
creates directories : 'mkdir'
remove files : 'rm [file-name]'
removes empty directories : 'rmdir [can-enter-dir-name]'
force remove a directory : 'rm -rf [file-or-dir-name]'
**Tip: never user 'rm -rf' in root directory.**

