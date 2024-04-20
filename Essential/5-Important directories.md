### Linux Directories

#### /etc
- Contains configuration files for Linux applications and programs.

#### /bin
- Holds essential command-line tools and programs.

#### /lib
- Contains Linux linked library files (DLL) used by binary files.

#### /var/log
- Stores log files from the system for troubleshooting purposes.
  - **syslog**: Logs all programs that do not have a specified log type (excluding kernel logs).
  - **klog**: Contains Linux kernel-specific logs.
  - **dmesg**: Allows viewing real-time kernel messages.

### Linux Processes

- **Processes**: Tasks from programs that are executed in the CPU.

#### ps
- Shows Linux processes, providing a list of running programs.

#### top
- Provides an interactive live display of processes.
#### htop
- Better version of Top command.
#### free
- Shows information about free memory.

#### Managing Processes

- **Show all user processes**: `ps -aux`
- **Kill a process with PID**: `kill [pid]`

### Zombie Processes
- Zombie processes are processes whose parent is dead or does not have a parent because the parent process is killed.
