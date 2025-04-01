# 📌 Base Command

## 🔹 Directory Navigation
| Command       | Description |
|--------------|------------|
| `pwd`       | Displays the current directory path |
| `ls`        | Lists files in the directory |
| `ls -l`     | Detailed list |
| `ls -a`     | Also shows hidden files |
| `cd <dir>`  | Changes directory |
| `cd ..`     | Moves up to the parent directory |
| `cd ~`      | Moves to the user's home directory |
| `cd -`      | Moves back to the previous directory |

## 📂 File and Directory Management
| Command               | Description |
|----------------------|-------------|
| `touch <file>`       | Creates an empty file |
| `mkdir <dir>`        | Creates a directory |
| `rm <file>`          | Deletes a file |
| `rm -r <dir>`        | Deletes a directory and its contents |
| `cp <file1> <file2>` | Copies a file |
| `cp -r <dir1> <dir2>`| Copies a directory |
| `mv <src> <dest>`    | Moves or renames a file/directory |
| `du -sh <dir>`       | Displays the space used by a directory |

## 👥 Group Management
| Command                        | Description |
|--------------------------------|-------------|
| `groupadd <groupname>`         | Creates a new group |
| `groupdel <groupname>`         | Deletes a group |
| `groupmod -n <newname> <oldname>` | Renames a group |

## 🔄 Assigning Users to Groups
| Command                                    | Description |
|--------------------------------------------|-------------|
| `usermod -aG <groupname> <username>`      | Adds a user to a group (append) |
| `gpasswd -a <username> <groupname>`       | Adds a user to a group |
| `gpasswd -d <username> <groupname>`       | Removes a user from a group |
| `id <username>`                            | Displays user ID (UID) and group ID (GID) |
| `groups <username>`                        | Shows groups a user belongs to |
| `getent group <groupname>`                 | Lists members of a specific group |

## 🛠️ Special Groups and Sudo Privileges
| Command                                    | Description |
|--------------------------------------------|-------------|
| `usermod -aG sudo <username>`             | Grants sudo privileges to a user (Debian/Ubuntu) |
| `usermod -aG wheel <username>`            | Grants sudo privileges to a user (RHEL/CentOS) |
| `visudo`                                   | Edits the sudoers file securely |
| `whoami`                                   | Displays the current user |
| `who`                                      | Shows who is logged in |
| `w`                                        | Displays active users and their processes |

## 🔍 Viewing and Editing Files
| Command           | Description |
|------------------|-------------|
| `cat <file>`     | Displays the content of a file |
| `tac <file>`     | Displays the content in reverse order |
| `less <file>`    | Allows reading large files |
| `head <file>`    | Shows the first 10 lines |
| `tail <file>`    | Shows the last 10 lines |
| `tail -f <file>` | Follows the file output in real time |
| `nano <file>`    | Nano text editor |
| `vim <file>`     | Vim text editor |

## 🔎 Search
| Command                    | Description |
|---------------------------|-------------|
| `find <path> -name <file>` | Searches for a file by name |
| `grep "text" <file>`     | Searches for a word in a file |
| `grep -r "text" <dir>`   | Recursively searches in a directory |

## 🛠️ Permissions and Ownership
| Command                    | Description |
|---------------------------|-------------|
| `chmod 755 <file>`        | Changes file permissions |
| `chown user:group <file>` | Changes the owner of a file |

## 📦 Process Management
| Command          | Description |
|-----------------|-------------|
| `ps aux`       | Displays running processes |
| `kill <PID>`   | Terminates a process by its PID |
| `killall <name>`| Terminates all processes with a given name |
| `top`          | Displays active processes in real time |
| `htop`         | Advanced version of top |

## 📡 Network
| Command            | Description |
|-------------------|-------------|
| `ping <host>`     | Checks connectivity with a host |
| `ifconfig`        | Displays network information (deprecated, use ip addr) |
| `ip addr show`    | Displays IP addresses |
| `netstat -tulnp`  | Shows open ports and listening services |

## 💾 Package Management
### Debian/Ubuntu
| Command                | Description |
|-----------------------|-------------|
| `apt update`         | Updates the package index |
| `apt upgrade`        | Upgrades installed packages |
| `apt install <pkg>`  | Installs a package |
| `apt remove <pkg>`   | Removes a package |

### CentOS/RHEL
| Command                | Description |
|-----------------------|-------------|
| `yum install <pkg>`  | Installs a package |
| `yum remove <pkg>`   | Removes a package |

## 🛠️ Disk Management
| Command            | Description |
|-------------------|-------------|
| `df -h`         | Displays free disk space in a readable format |
| `du -sh <dir>`  | Displays the space used by a directory |
| `fdisk -l`      | Shows partition information |
| `mount <dev> <mnt>` | Mounts a device to a mount point |
| `umount <mnt>`  | Unmounts a device |

## 🏁 Exit
| Command    | Description |
|-----------|-------------|
| `exit`   | Exits the terminal session |
| `logout` | Logs out the user |
