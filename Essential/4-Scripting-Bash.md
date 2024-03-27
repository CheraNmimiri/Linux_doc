### Bash Scripting Basics

#### Interpreter Paths
- **sh**: `/bin/sh`
- **bash**: `/bin/bash`
- **tsch, csh, zsh**: Interpreter paths may vary

#### Variables
- **$1**: First argument (used for calling variables)
- **$2**: Second argument
- **$?**: Exit code
  - The exit code, retrieved using `$?`, indicates the status of the last executed command. 

#### Making and Running a Bash Script

1. **Create a Bash or SH File**
   - Create a file with a `.sh` extension, e.g., `name.sh`.

2. **Use Nano Editor to Write Bash Code**
   - Open the file with Nano editor: `nano [file-name]`.
   - Write your Bash code.

3. **Add Bash Interpreter Declaration**
   - Add `#!/bin/bash` at the beginning of the file to specify the Bash interpreter.

4. **Give Execution Permission**
   - Use ```bash `chmod +x [file-name]` ``` to grant execution permission to the file.

6. **Run the Script**
   - Execute the file with ```bash `./[file-name]` ``` 

#### Using Temporary Variables
- You can use temporary variables like `$n` (where n is any number) to store values and pass arguments.
- When running the script, provide values for the variables as arguments: ```bash `./[file-name] value1 value2` ```

#### If Syntax
```bash
#!/bin/bash
if [ "$1" = "Hello world" ]; then
	echo "$hello back"
else
	echo "$bye"
fi
```

#### Example Bash Code
```bash
#!/bin/bash
cd sh > /dev/null 2>&1

if [ "$? != "0" ]; then
	echo "There is no sh directory!"
else
	echo "OK, now I am in `pwd` path"
fi
```
- `> /dev/null 2>&1`: Redirects standard output and standard error to null device to suppress errors if the directory doesn't exist.

#### Command Execution Inside Quotes
- Commands enclosed in double quotes `""` execute within backticks ```` ```, and the output is displayed.

#### For Syntax
```bash
#!/bin/bash
for x in {1..12}; do 
	echo "$x"
done

# Example 
for loop in `ls`; do
	echo "$loop"
done
```

These are the fundamental aspects of writing and executing Bash scripts. You can extend them with various commands and structures to achieve complex tasks efficiently.
