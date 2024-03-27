### Security and Permissions

#### User Types
- **root**: Super user or administrator with access to kernel.
- **Standard Users**: Normal users with or without administrative rights.
  - **With Administrative Rights**
  - **Without Administrative Rights**
- **System Users**: Service accounts and network accounts.
  - **Service Account**: Created explicitly to provide a security context for services running on the system.
  - **Network Account**: Used by the service control manager with minimum privileges on the local computer.

#### Tools for Recognizing Users
- `id`: Shows information about users.
- `w`: Displays what logged in users are doing.
- `who`: Shows who is logged in.
- `whoami`: Displays the current user.

#### Files about Users
- **/etc/passwd**: Contains user account information including usernames, user IDs, group IDs, home directories, and default shells.
- **/etc/group**: Holds group information such as group names, group IDs, and a list of users who are members of each group.
- **/etc/shadow**: Contains encrypted password information for user accounts, readable only by the root user.

#### Increasing Access Level
- **su [user-name]**: Switches user.
- **[sudo]**: Substitute user.

#### User ID (UID) Information
- **0**: Root user.
- **1 to 499**: Service accounts.
- **500 to 6000**: Standard users.
- **6000 and above**: Network users.

#### Note
- When using `ls` in the home directory, it shows standard users.
