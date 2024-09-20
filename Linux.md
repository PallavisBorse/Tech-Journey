### Linux Notes: Basic to Advanced

---

#### 1. **Introduction to Linux**
- **What is Linux?**
  - Open-source operating system based on Unix.
  - Multiuser and multitasking capabilities.

---

#### 2. **Basic Commands**
- **File and Directory Operations:**
  - `ls` - List directory contents.
  - `cd` - Change directory.
  - `pwd` - Print working directory.
  - `mkdir` - Create a directory.
  - `rmdir` - Remove an empty directory.
  - `rm` - Remove files or directories.
  - `cp` - Copy files/directories.
  - `mv` - Move or rename files/directories.

- **Viewing and Editing Files:**
  - `cat` - Display file contents.
  - `less` - View file content page by page.
  - `nano`/`vim` - Text editors for editing files.

---

#### 3. **Understanding Paths**
- **Absolute Path:** Full path from the root (e.g., `/home/user/file.txt`).
- **Relative Path:** Path relative to the current directory (e.g., `../file.txt`).

---

#### 4. **File Permissions and Ownership**
- **Viewing Permissions:**
  - `ls -l` - List files with permissions.
- **Changing Permissions:**
  - `chmod` - Change file permissions (e.g., `chmod 755 file`).
- **Changing Ownership:**
  - `chown` - Change file owner (e.g., `chown user:group file`).

---

#### 5. **Links in Linux**
- **Symbolic Links:**
  - `ln -s target linkname` - Create a symbolic link.
- **Hard Links:**
  - `ln target linkname` - Create a hard link.

---

#### 6. **Process Management**
- **Viewing Processes:**
  - `ps` - Show current processes.
  - `top` - Real-time view of running processes.
- **Managing Processes:**
  - `kill` - Terminate a process using PID.
  - `bg` - Background a process.
  - `fg` - Bring a process to the foreground.

---

#### 7. **Networking Commands**
- **Basic Networking:**
  - `ping` - Check network connectivity.
  - `ifconfig`/`ip` - Display network interface configuration.
  - `netstat` - Display network connections.
  - `scp` - Secure copy files between hosts.

---

#### 8. **Searching and Finding Files**
- **Using Search Commands:**
  - `grep` - Search for patterns in files.
  - `find` - Search for files in a directory.
  - `locate` - Find files quickly by name.

---

#### 9. **Archiving and Compression**
- **Using Archive Tools:**
  - `tar` - Archive files (e.g., `tar -cvf archive.tar dir/`).
  - `gzip`/`gunzip` - Compress and decompress files.

---

#### 10. **Shell Scripting Basics**
- **Creating a Script:**
  - Use `nano script.sh` to create a script file.
  - Make executable: `chmod +x script.sh`.
  - Run a script: `./script.sh`.

---

#### 11. **User Management**
- **Basic User Commands:**
  - `useradd` - Add a new user.
  - `passwd` - Change a user’s password.
  - `usermod` - Modify user account details.

---

#### 12. **Environment Variables**
- **Viewing and Setting Variables:**
  - `echo $VARIABLE` - Display a variable.
  - `export VARIABLE=value` - Set a new variable.

---

#### 13. **System Logs**
- **Viewing Logs:**
  - Log files located in `/var/log/`.
  - `tail -f /var/log/syslog` - View real-time updates of log files.

---

#### 14. **Cron Jobs and Scheduling**
- **Automating Tasks:**
  - `crontab -e` - Edit user’s cron jobs.
  - Cron syntax: `* * * * * command` (minute, hour, day, month, weekday).

---

#### 15. **Security and Firewall**
- **Basic Security Practices:**
  - Keep the system updated.
  - Use strong passwords.
- **Configuring Firewalls:**
  - Use `iptables` or `ufw` to manage firewall rules.

---

#### 16. **Virtualization and Containers**
- **Understanding Virtualization:**
  - Tools: `KVM`, `VirtualBox`.
- **Introduction to Containers:**
  - Basics of Docker and common commands (e.g., `docker run`, `docker ps`).

---

#### 17. **Package Management**
- **Using Package Managers:**
  - **Debian-based:** `apt-get` (e.g., `apt-get install package`).
  - **Red Hat-based:** `yum` or `dnf` (e.g., `yum install package`).

---

#### 18. **Backup and Recovery**
- **Backup Strategies:**
  - Using `rsync` for file backups.
- **Data Recovery Basics:**
  - Tools like `testdisk` and `photorec`.

---

#### 19. **Advanced Shell Features**
- **Command History:**
  - `history` - View command history.
  - `!!` - Execute the last command.
- **Pipes and Redirection:**
  - `|` - Pipe output to another command.
  - `>` - Redirect output to a file.

---

#### 20. **File System Hierarchy**
- **Understanding Linux File System:**
  - `/` - Root directory.
  - `/home` - User home directories.
  - `/etc` - Configuration files.
  - `/var` - Variable files (e.g., logs).
  - `/tmp` - Temporary files.

---

### Tips for Study:
- Practice commands in a terminal.
- Use online resources and Linux documentation (man pages).
- Build small projects or scripts to reinforce learning.
