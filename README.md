# oss-audit-24BAI10676
# Open Source Audit Capstone Project

**Student Name:** [Aditya Patel]  
**Registration Number:** [24BAI10676]  
**Target Software Audited:** [VLC Media Player]  

## Project Overview
This repository contains the practical technical component of the Open Source Audit Capstone project. It includes five automated shell scripts developed to demonstrate practical Linux command-line skills, system administration techniques, and an understanding of the Free and Open Source Software (FOSS) ecosystem. 

## Included Scripts
1. **`1_system_identity.sh`**: A system dashboard script that fetches and displays the current Linux distribution, kernel version, active user, system uptime, and the underlying OS license.
2. **`2_package_inspector.sh`**: Checks the local package manager to verify if the target software is installed, retrieves its version details, and outputs a brief philosophical statement about the project.
3. **`3_disk_auditor.sh`**: Uses looping structures to iterate through critical system directories (and the target software's configuration path), reporting on file sizes, ownership, and permission structures.
4. **`4_log_analyzer.sh`**: Parses a specified system log file line-by-line to count occurrences of a specific keyword (e.g., "error" or "install") and outputs the most recent matches for troubleshooting.
5. **`5_manifesto_generator.sh`**: An interactive script that prompts the user with questions regarding their views on FOSS and generates a customized, timestamped text file containing their personal open-source manifesto.

## Prerequisites
To run these scripts, you will need:
- A Linux environment (Ubuntu desktop, a Virtual Machine, or Windows Subsystem for Linux (WSL)).
- Standard GNU core utilities (`bash`, `awk`, `grep`, `cat`, `cut`, `du`, `ls`).
- `dpkg` or `rpm` package manager.

## Execution Instructions
Follow these steps to run the scripts on your local Linux system:

**1. Clone the repository:**
```bash
git clone [https://github.com/](https://github.com/)Aditya8764/oss-audit-24BAI10676.git
cd oss-audit-24BAI10676
