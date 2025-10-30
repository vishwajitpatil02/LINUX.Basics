# LINUX.Basics
Basic commands of linux 

Repository: linux-basic-commands
# Folder Structure

# linux-basic-commands/
│
├── README.md
├── commands/
│   ├── file_management.md
│   ├── user_management.md
│   ├── permissions.md
│   ├── network_commands.md
│   └── system_info.md
│
└── examples/
    ├── script_examples.sh
    └── practice_tasks.md

    #  Linux Basic Commands

Welcome to **Linux Basic Commands** — a simple guide for beginners learning the Linux command line.

## Topics Covered
- File Management Commands
- User Management Commands
- Permissions and Ownership
- System Information
- Shell Script Examples

---

##  How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/vishwajitpatil02/linux-basic.git

2. Open any .md file inside the commands folder to learn specific commands.

3.Try examples in the examples folder to practice.

## Example Commands
ls -l        # List files in long format
pwd          # Print working directory
whoami       # Display current user

Created by [Vishwajitpatil]

Happy Learning! 


---

### **commands/file_management.md**
```markdown
#  File Management Commands

| Command | Description |
|----------|--------------|
| `ls` | List files and directories |
| `cd` | Change directory |
| `pwd` | Show current working directory |
| `cp source destination` | Copy files or directories |
| `mv source destination` | Move or rename files |
| `rm filename` | Delete a file |
| `mkdir foldername` | Create a directory |
| `rmdir foldername` | Remove an empty directory |
| `cat filename` | Display file contents |
| `touch filename` | Create an empty file |

#  User Management Commands

| Command | Description |
|----------|--------------|
| `useradd username` | Create a new user |
| `passwd username` | Set or change password |
| `usermod -aG group username` | Add user to group |
| `deluser username` | Delete a user |
| `groups username` | Show user’s groups |
| `who` | Show logged-in users |
| `id username` | Display user ID and groups |


# File Permissions in Linux

| Command | Description |
|----------|--------------|
| `chmod 755 filename` | Change file permissions |
| `chown user:group filename` | Change file owner and group |
| `ls -l` | Show permissions of files |
| `umask` | Show or set default permissions |
| `sudo` | Run a command as another user (usually root) |

**Example:**
```bash
chmod 700 myscript.sh   # Only owner can read, write, execute


#  System Information Commands

| Command | Description |
|----------|--------------|
| `uname -a` | Show system info |
| `top` | Display running processes |
| `df -h` | Show disk space usage |
| `free -m` | Show memory usage |
| `uptime` | Show system uptime |
| `hostname` | Show system name |


# examples/script_examples.sh
#!/bin/bash

# Simple script to show system info

echo "System Information:"
uname -a

echo "Disk Usage:"
df -h

echo "Memory Usage:"
free -m


# examples/practice_tasks.md
#  Linux Practice Tasks

✅ Create a new user called `student`  
✅ Make a group `developers` and add `student` to it  
✅ Create a file `/home/student/info.txt`  
✅ Change ownership of the file to `student`  
✅ Give only read permission to others  
✅ Try `ping google.com` and save output to `ping_result.txt`  
✅ Write a shell script that displays system uptime


