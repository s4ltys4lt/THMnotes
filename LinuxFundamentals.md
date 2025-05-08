# THMnotes
# Linux Fundamentals – TryHackMe Walkthrough

🗓️ **Date Completed:**  12/2/25 
🏷️ **Room Link:** [TryHackMe - Linux Fundamentals](https://tryhackme.com/room/linuxfundamentals)

---

## 📘 Room Summary

The Linux Fundamentals room is a beginner-friendly introduction to the Linux operating system. It walks through key topics such as file system structure, user and group management, permissions, navigation, basic commands, package management, and file editing tools. This room helps build a strong foundation for using Linux in cybersecurity and server administration contexts.

---

## 🛠️ Tools / Commands Covered

- `ls`, `cd`, `pwd`, `touch`, `mkdir`, `rm`, `cp`, `mv`
- `chmod`, `chown`, `cat`, `less`, `more`, `nano`, `vi`
- `apt`, `dpkg`, `ps`, `top`, `kill`, `man`, `whoami`
- File permission notation (rwx), and user/group ownership

---

## 🔍 Key Concepts Learned
🔹 File System Navigation
Learned how to use pwd, ls, cd to move around the Linux file system.

Understood absolute vs. relative paths.

Saw the structure of Linux directories like /home, /etc, /var.

🔹 File & Directory Management
Used touch, mkdir, rm, cp, mv to create, remove, and manage files.

Learned to use ls -l and ls -a to list files and permissions.

🔹 Permissions and Ownership
Practiced reading permission strings like -rwxr-xr--.

Changed file permissions with chmod (numeric and symbolic).

Changed ownership with chown and chgrp.

🔹 Package Management
Used apt update, apt upgrade, and apt install to manage software.

Learned the difference between apt and dpkg.

🔹 Process Management
Viewed running processes with ps aux and top.

Killed processes with kill [PID].

🔹 User and Group Management
Learned about adduser, passwd, and how Linux handles users.

Checked user info in /etc/passwd and group info in /etc/group.

🔹 Text File Viewing and Editing
Used cat, less, more to read files.

Edited files with nano and vi, learning basic commands for both.

🔹 Getting Help
Used man and --help flags to find command documentation.
### 🔹 File System Navigation
```bash
cd /home/user
pwd
ls -la
