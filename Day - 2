# 🐧 Day -2: Linux Login Prompt, Directory Structure & System Folders

## 🔐 Linux Login Prompt Explained

When you first log in to a Linux machine, you might see something like:

**root@ubuntu-dev:/#**

### Breakdown:
- `root` → Logged-in user (superuser)  
- `ubuntu-dev` → Hostname of the machine  
- `/` → Current working directory (root directory)  

If you create another user (e.g., `ubuntu`), the prompt may look like:

**ubuntu@hostname:~$**

- `~` → Represents the user's home directory, which is `/home/ubuntu`

---

## 📁 Listing Files with `ls -ltr`

**ls -ltr**

- `ls` → List directory contents  
- `-l` → Long listing format  
- `-t` → Sort by modification time  
- `-r` → Reverse order  

This command shows files sorted by time, newest last.

---

## 📂 Linux Directory Structure Overview

Linux has a hierarchical directory structure starting from `/` (root). Some important directories include:

| Directory | Purpose |
|----------|---------|
| `/boot`  | Contains boot loader files and the Linux kernel |
| `/bin`   | Essential user binaries (e.g., mkdir, passwd, sudo) |
| `/sbin`  | System binaries for administrative tasks (e.g., useradd, userdel) |
| `/lib`   | Libraries used by the kernel for system calls |
| `/usr`   | Secondary hierarchy for user-installed software |
| `/srv`   | Server-related data (e.g., web server configs) |
| `/opt`   | Optional third-party software (e.g., custom Java installations) |
| `/mnt`   | Temporary mount point for external volumes |
| `/var`   | Stores log files and third-party libraries |
| `/root`  | Home directory of the root user |
| `/dev`   | Contains device files (e.g., hard drives, USBs) |
| `/proc`  | Virtual filesystem for kernel and process information |
| `/sys`   | Interface to kernel and hardware configuration |
| `/tmp`   | Temporary files and directories (cleared on reboot) |
| `/home`  | User-specific directories |
| `/etc`   | System configuration files (similar to C: drive in Windows) |

---

## 🧰 /bin vs /sbin – What’s the Difference?

### 🔹 /bin – User Binaries

Contains essential command binaries for all users:

- `sudo` → Run commands as superuser  
- `su` → Switch user  
- `mkdir` → Create directories  
- `passwd` → Change user password  

### 🔸 /sbin – System Binaries

Contains administrative commands used by the root user:

- `useradd` → Add new user  
- `userdel` → Delete user  
- `reboot` → Restart system  

> Both `/bin` and `/sbin` are also found inside `/usr/bin` and `/usr/sbin` for user-installed software.

---

## 📦 /opt – Optional Software Packages

Used for third-party applications and custom dependencies.

Example: Installing a specific version of Java or Node.js.

Why not install in `~/` (home folder)?
- Because multiple users may need access.
- `/opt` is system-wide, while `~` is user-specific.

> This is the difference between people who use Linux casually and those who understand Linux deeply.

---

## 💾 /mnt – Mount Point

Used by system administrators to mount external storage or volumes.

Example: Mounting a USB drive or a new disk partition:

**sudo mount /dev/sdb1 /mnt**

---
