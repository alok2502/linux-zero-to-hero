
📘 Linux in One Shot
Date: 14/11/2023  
Source: Train with Shubham  

---

🌐 How Does the Internet Work?

- The internet works via optical fibers that connect users to data centers.
- Data centers are clusters of computers that store and transmit data using cables.

`
[Flow Diagram]
Person → ISP → Optical Fiber → Data Center
`

- ISP: Internet Service Provider  
- IP Address: Unique identifier for devices on the internet

---

🖥️ What Is a Server?

- A server is a computer that serves data to clients.
- A client (phone, laptop, etc.) requests information from the server.

`
[Example]
You search "YouTube" in your browser:
→ ISP provides internet access  
→ Optical fiber streams data  
→ Data center serves the content
`

---

🔄 Web Server vs Application Server

| Server Type        | Purpose               | Example         |
|--------------------|------------------------|------------------|
| Web Server         | Serves static content  | Nginx            |
| Application Server | Serves dynamic content | Node.js App      |

---

🧠 Types of Applications

1. Standalone Application  
   - Doesn’t require internet or database  
2. Web Application  
   - Runs on the internet  
   - Supported by multiple servers

---

🐧 Introduction to Linux

- Linux is an open-source operating system.
- Acts as an intermediate layer between hardware and software.
- Unix is the commercial version (e.g., macOS).
- Linux is the open-source alternative.

---

🪟 Linux vs Windows

| Feature           | Linux                              | Windows                          |
|------------------|-------------------------------------|----------------------------------|
| License          | GPL (General Public License)        | Commercial                       |
| Focus            | Dev, Terminal, Networking, Scripting| General use (media, games, etc.)|
| Antivirus Needed | ❌ No                               | ✅ Yes                            |

---

🔐 Remote Server Tools

- RDP: Remote Desktop Protocol  
- SSH: Secure Shell

`
[Diagram]
User → RDP/SSH → Virtual Machine
`

---

🧩 Linux Core Components

- Bootloader: Starts GRUB and loads OS files  
- Kernel: Heart of Linux, manages hardware and system calls  
- Shell: Interface between user and kernel

`
[Architecture Diagram]
Application → Shell → Kernel → Hardware
`

---

🧾 Day 2: Linux Commands

`bash

File & Directory
ls           # List files
mkdir        # Make directory
ls -l        # Detailed list
pwd          # Present working directory
cd           # Change directory
clear        # Clear terminal
rm           # Remove file
rmdir        # Remove directory
rm -r        # Remove recursively

File Reading
cat          # Read file
zcat         # Read compressed file
head         # Show top lines
tail         # Show bottom lines
tail -f      # Follow file updates
less         # Page-by-page view
more         # Similar to less

File Operations
cp           # Copy
mv           # Move/Rename
wc           # Word count

Links
Hard Link    # Shortcut persists even if original is deleted  
Soft Link    # Shortcut breaks if original is deleted
`

---

🧾 Day 3: More Commands

`bash

Text & File Utilities
cut          # Cut words from line
tee          # Output to screen & file
sort         # Sort lines
diff         # Compare files

System & Network
ssh          # Secure shell login
df -h        # Disk space (human-readable)
du           # Disk usage
top          # Show running processes
kill         # Kill a process
free -m      # RAM usage

System Info
uname        # Platform info
uptime       # System uptime
date         # Current date/time
who          # Logged-in users
whoami       # Current user
`

---