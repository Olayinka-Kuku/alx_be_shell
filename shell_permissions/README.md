# Project Scripts
## Shell Permissions Scripts
### 0-iam_betty
This script switches the current user to the user 'betty' .

### 1-who_am_i
This script prints the effective username of the current user by using the `whoami` command.

### 4-empty
This script creates an empty file named `hello`.

### 5-execute
This script adds execute permission to the owner of the file `hello`.

### 6-multiple_permissions
This script adds execute permissions to the owner and group owner of the file `hello`, and read permissions to all other users. It uses the `chmod` command to set these permissions.

### 9-John_Doe
This script sets the file permissions of `hello` to `-rwxr-x-wx`. It uses the `chmod` command with mode `753` to achieve this permission setting.
