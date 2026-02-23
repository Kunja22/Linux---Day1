# Linux---Day1
Linux Administration Labs including User Management, File Permission, Process Control and Vim Editor practice.

# Linux Administration Labs

This repository contains hands-on Linux administration labs demonstrating core system management concepts including user management, file permissions, process control, and text editing using Vim.

---

## Objective
To create and manage user accounts in a Linux environment.

## Commands Executed

### Create a New User
```bash
sudo useradd -m riya

# Set User Password
sudo passwd riya

Verify User Details
id riya

Switch to New User
su - riya

📌 Lab 2: File Permissions & Ownership

# Check File Permissions
ls -l filename

# Modify Permissions (Numeric Mode)
chmod 755 filename
# Change File Ownership
sudo chown riya filename

📌 Lab 3: Process Management

# View Running Processes
ps -ef

# Real-Time Process Monitoring
top

# Terminate Process by PID
kill <PID>

📌 Lab 4: Text Editing with Vim

# Open or Create File
vim filename

# Save and Exit
:wq









