# 🔐 SSH (Secure Shell)

## 📌 What is SSH?

**SSH (Secure Shell)** is a **cryptographic network protocol** used to securely connect to a **remote server** from a **local computer** using command-line commands.

In simple words:  
SSH lets you **control a remote machine safely**, even if that machine is located somewhere in the cloud.

---

## 🖥️ Architecture Overview

![SSH Architecture](./ssh-diagram.png)

### Components:
- **Local Computer**  
  Your personal system (laptop/PC) where you run SSH commands.
- **SSH Protocol**  
  Provides encrypted communication between the local machine and the remote server.
- **Remote Server**  
  A server or virtual machine hosted in the cloud (e.g., GCP, AWS, Azure).

---

## 🔄 How SSH Works (Step-by-Step)

1. You open a terminal on your **local computer**.
2. You initiate an SSH connection using a command like:
   ```bash
   ssh username@server_ip

   
🌍 Real-World Use Case

In my real experience, I used SSH while working with a Google Cloud Platform (GCP) Virtual Machine, even before fully knowing what SSH was.

The VM was running somewhere in the cloud

To access it, I had to initiate a secure shell connection

Once connected, I could:

Run commands

Install software

Manage files

Control the VM completely via terminal

Without SSH, securely accessing and managing cloud VMs would not be possible.