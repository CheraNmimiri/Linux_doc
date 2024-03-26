### Basic Commands

#### Change User Password
To change a user's password:
```bash
passwd [user]
```

#### Show List of Files and Directories
To display a list of files and directories:
```bash
ls
```

#### Show Permissions
To show permissions used:
```bash
ls -l
```

#### Show All, Including Hidden Files
To show all files, including hidden ones:
```bash
ls -a
```

#### Recursive View
To recursively view all files and directories:
```bash
ls -R
```

#### Clear Terminal
To clear the terminal:
```bash
clear
```

#### Symbol for Home Directory
Symbol for the home directory:
```bash
~
```

#### Show File Details
To show details of a file:
```bash
cat [file-name]
```

#### Print Text
To print text:
```bash
echo ['text']
```

#### Symbol for Variables
Symbol used to call a variable:
```bash
$ # Example: a=5, echo $a
```

#### Symbol for Commands
Symbol for commands:
```bash
;
```

#### Globbing
To show files with specific suffix:
```bash
ls *.txt # Shows all files with .txt extension
ls file??.txt # Shows files starting with 'file' and followed by any two characters and .txt
```

#### Watch Command
Similar to viewing environment variables in Windows:
```bash
echo $PATH
```

#### Show Command Path
To show the path of a terminal command:
```bash
whereis [command-name]
```

#### Show Current Path
To show your current path:
```bash
pwd
```

#### Show Manual of Command
To view the manual of a command:
```bash
man [command-name]
```

#### Update Manual
To update the manual and add new manuals:
```bash
sudo mandb
```

#### Search Key in Manuals
To search a key in all manual contexts:
```bash
man -k [key-name]
```

#### Show Simple Manual
To show a simplified manual:
```bash
info [command-name]
```

#### Brief Description of Command
To get a brief description about a command:
```bash
whatis [command-name]
```

#### Show Details of Zip File
To view the details of a zip file:
```bash
less [file-name]
```

#### Access All Documents
Accessing all documents:
```bash
/usr/share/doc
```

### Tips
- Using `cd` command without any argument brings you back to the home directory.
- Creating Empty File or Updating Last Access Time: 
```bash
touch [file-name]
```
- Removing Files or Directories:
```bash
rm [file-or-directory-name]
```
- Moving or Renaming Files and Folders:
```bash
mv [file-or-directory-name] [destination]
```
- Copying Files or Directories:
```bash
cp [filename] [des-path]
```
- Copying Directory to Directory:
```bash
cp -R [dir_name] [destination-dir]
```
- Creating Directories:
```bash
mkdir
```
- Removing Empty Directories:
```bash
rmdir [can-enter-dir-name]
```
- Forcibly Removing a Directory (Caution!):
```bash
rm -rf [file-or-dir-name] # Never use 'rm -rf' in root directory.
```
