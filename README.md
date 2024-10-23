# 📁 **Linux Commands Cheat Sheet**

This repository contains a **complete guide to Linux commands** with examples, explanations, and tricks to help you master the Linux terminal. Whether you're a beginner or an advanced user, this project will serve as a helpful reference.

---

## 🚀 **Project Setup**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/linux-commands-guide.git
   cd linux-commands-guide
   ```

---

## 🛠️ **Basic Commands**

| **Command**        | **Description**                  |
|--------------------|----------------------------------|
| `pwd`              | Print current working directory |
| `ls`               | List files and directories      |
| `cd`               | Change directory                |
| `mkdir`            | Create a new directory          |
| `touch`            | Create an empty file            |
| `cp source target` | Copy files or directories       |
| `mv source target` | Move/rename files or directories|
| `rm`               | Remove files or directories     |
| `clear`            | Clear terminal screen          |

---

## 🔍 **File Viewing and Searching**

| **Command**            | **Description**                         |
|------------------------|------------------------------------------|
| `cat file.txt`         | Display file contents                   |
| `less file.txt`        | View file content one page at a time    |
| `head -n 10 file.txt`  | View first 10 lines of a file           |
| `tail -n 10 file.txt`  | View last 10 lines of a file            |
| `grep "text" file.txt` | Search for a string within a file       |
| `find /dir -name "*.txt"` | Find files by name pattern           |

---

## 🧑‍💻 **User and Permissions Management**

| **Command**            | **Description**                                  |
|------------------------|--------------------------------------------------|
| `whoami`               | Display current username                        |
| `id`                   | Show user and group IDs                         |
| `sudo`                 | Execute command as another user (root)          |
| `chmod 755 file.txt`   | Change file permissions                         |
| `chown user:group file.txt` | Change file owner                          |

---

## ⚙️ **Networking Commands**

| **Command**            | **Description**                           |
|------------------------|--------------------------------------------|
| `ifconfig`             | Display network interfaces (deprecated)  |
| `ip a`                 | Show IP addresses                        |
| `ping google.com`      | Test network connection                  |
| `curl url`             | Fetch a webpage                          |
| `wget url`             | Download a file from a URL               |

---

## 📦 **Package Management**

| **Command**            | **Description**                           |
|------------------------|--------------------------------------------|
| `apt update`           | Update package lists (Debian-based distros) |
| `apt install package`  | Install a package                         |
| `yum install package`  | Install package (Red Hat-based distros)   |
| `snap install package` | Install a snap package                    |
| `dpkg -i package.deb`  | Install a .deb package                    |

---

## 🗂️ **Archive and Compression Commands**

| **Command**            | **Description**                           |
|------------------------|--------------------------------------------|
| `tar -cvf archive.tar dir` | Create a tar archive                 |
| `tar -xvf archive.tar`  | Extract a tar archive                    |
| `gzip file.txt`         | Compress a file using gzip               |
| `gunzip file.txt.gz`    | Decompress a gzip file                   |
| `zip archive.zip file`  | Compress files into a zip archive        |
| `unzip archive.zip`     | Extract files from a zip archive         |

---

## 📊 **Process Management**

| **Command**            | **Description**                           |
|------------------------|--------------------------------------------|
| `ps aux`               | List all processes                       |
| `top`                  | Display running processes in real-time   |
| `kill PID`             | Terminate a process by its PID            |
| `htop`                 | Interactive process viewer (requires install) |
| `killall process_name` | Kill processes by name                    |

---

## 🛡️ **System Monitoring & Management**

| **Command**            | **Description**                           |
|------------------------|--------------------------------------------|
| `df -h`                | Show disk space usage                    |
| `du -sh dir`           | Show size of a directory                 |
| `free -h`              | Display memory usage                     |
| `uptime`               | Show how long the system has been running|
| `uname -a`             | Show system information                  |
| `reboot`               | Restart the system                       |

---

## 🛠️ **Advanced Commands and Tricks**

### 1. **Create Aliases (Shortcuts)**
```bash
alias ll='ls -lah'
```
Add this line to `~/.bashrc` to make it permanent.

### 2. **View Hidden Files**
```bash
ls -a
```

### 3. **Redirect Output to a File**
```bash
ls > output.txt
```

### 4. **Chain Commands**
```bash
mkdir test && cd test
```

### 5. **Run Commands in the Background**
```bash
command &
```

### 6. **View Command History**
```bash
history
```

---

## 🧰 **Version Control with Git Commands**

| **Command**               | **Description**                          |
|---------------------------|-------------------------------------------|
| `git init`                | Initialize a new repository               |
| `git add .`               | Stage all changes                        |
| `git commit -m "message"` | Commit changes                           |
| `git push origin main`    | Push changes to the remote repo           |
| `git pull origin main`    | Pull latest changes from remote repo      |
| `git status`              | Show the status of your working directory |
| `git clone url`           | Clone a remote repository locally         |

---

## 📝 **Contributing**
Feel free to contribute to this project! Fork the repository, make your changes, and submit a pull request.

---

## 📦 **How to Use**

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/linux-commands-guide.git
   ```

2. Navigate to the project:
   ```bash
   cd linux-commands-guide
   ```

3. Explore the **Linux commands** and practice them!

---

## 📜 **License**
This project is licensed under the MIT License.

---

This project will not only help you master **Linux** but also serves as a quick reference for **everyday commands**! 🚀 Feel free to extend the list with more advanced commands as you explore Linux further.
