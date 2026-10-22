
# Linux Shell Scripting

A hands-on learning repository covering Linux Shell Scripting and Bash, from absolute basics to practical DevOps automation.

This repository documents my daily learning, hands-on practice, commands, scripts, troubleshooting, and mini-projects as I build practical Linux and DevOps skills.

## 🎯 Learning Objectives

- Learn Shell Scripting from scratch.
- Understand Bash syntax, variables, and user input.
- Automate repetitive Linux administration tasks.
- Work with conditions, loops, functions, and command-line arguments.
- Monitor Linux system resources and services.
- Build practical automation scripts for DevOps workflows.
- Improve scripting, debugging, and problem-solving skills.

## 🛠️ Technologies Used

- **Operating System:** Linux
- **Shell:** Bash
- **Version Control:** Git
- **Code Hosting:** GitHub
- **Virtualization:** VirtualBox
- **Cloud Platform:** AWS (for future cloud automation practice)

## 📚 Learning Roadmap

### 01. Shell Scripting Basics
- Introduction to Shell and Bash
- Shebang (`#!/bin/bash`)
- `echo` and `printf`
- Comments
- Variables
- User input using `read`
- Creating and executing shell scripts
- File permissions using `chmod`

### 02. Variables and Command-Line Arguments
- Local variables
- Environment variables
- Positional parameters: `$1`, `$2`
- `$@` and `$#`
- Exit status using `$?`

### 03. Conditional Statements
- `if`, `else`, and `elif`
- `test` and `[ ]`
- String comparisons
- Numeric comparisons
- File and directory checks

### 04. Loops
- `for` loops
- `while` loops
- `until` loops
- `break` and `continue`

### 05. Functions
- Creating functions
- Passing arguments to functions
- Returning exit statuses
- Reusable shell code

### 06. Files and Directories
- File and directory operations
- Reading files
- Processing text
- Searching logs with `grep`
- Text processing with `awk` and `sed`

### 07. Linux System Administration
- Disk usage monitoring
- Memory and CPU monitoring
- Process management
- Service status checks
- Log monitoring
- File backups

### 08. Error Handling and Best Practices
- Exit codes
- Input validation
- Logging
- Debugging with `bash -x`
- Safe scripting with `set -euo pipefail`
- Handling command failures

### 09. DevOps Automation Projects
- Linux system information script
- Disk usage monitoring script
- Service health-check script
- Log analysis script
- Automated backup script
- Deployment automation script
- AWS administration scripts

## 📂 Repository Structure

```text
linux-shell-scripting/
├── README.md
├── 01-basics/
│   ├── hello.sh
│   ├── variables.sh
│   └── user-input.sh
├── 02-conditions/
├── 03-loops/
├── 04-functions/
├── 05-files-and-directories/
├── 06-system-monitoring/
├── 07-automation-projects/
└── notes/
    └── shell-scripting-notes.md
```

*Directories and files will be added as the learning journey progresses.*

## 🚀 Getting Started

### Prerequisites

- Basic Linux command-line knowledge
- A Linux machine or virtual machine
- Bash shell
- Git installed

### Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/linux-shell-scripting.git
cd linux-shell-scripting
```

Replace `YOUR-USERNAME` with your GitHub username.

### Create Your First Script

```bash
vi hello.sh
```

Add the following code:

```bash
#!/bin/bash

echo "Hello, World!"
echo "Learning Linux Shell Scripting"
echo "Building practical DevOps skills"
```

Save the file and execute it:

```bash
bash hello.sh
```

Alternatively, make it executable:

```bash
chmod +x hello.sh
./hello.sh
```

## 💻 Sample Practice Scripts

### Display System Information

```bash
#!/bin/bash

echo "Current User:"
whoami

echo "Current Directory:"
pwd

echo "System Uptime:"
uptime

echo "Disk Usage:"
df -h

echo "Memory Usage:"
free -m
```

Save as `system-info.sh` and run:

```bash
bash system-info.sh
```

## 📈 Learning Progress

- [x] Created the repository and learning roadmap
- [ ] Completed Shell Scripting fundamentals
- [ ] Practiced variables and user input
- [ ] Learned conditional statements
- [ ] Practiced loops and functions
- [ ] Built Linux monitoring scripts
- [ ] Implemented error handling and logging
- [ ] Completed practical DevOps automation projects

## 🔄 Daily Learning Practice

My approach to learning:

1. Understand one concept at a time.
2. Practice it on a Linux virtual machine.
3. Write scripts and test different scenarios.
4. Document what I learned and the problems I solved.
5. Commit working scripts to GitHub.
6. Apply the concepts to real-world DevOps tasks.

## 🎯 Career Goal

To strengthen my practical Linux and Bash scripting skills and apply them to Cloud Engineering, DevOps, and Site Reliability Engineering (SRE).

This repository represents my hands-on practice, continuous learning, and progress toward building production-oriented automation skills.

## 🤝 Contributions

This is primarily a personal learning repository. Suggestions, feedback, and improvements are welcome.

## 📜 License

This repository is intended for educational and learning purposes. A license can be added when the repository's sharing and reuse terms are decided.

---

**Learning by doing | Automating with Bash | Growing toward DevOps and SRE**
