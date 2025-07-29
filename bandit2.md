# Bandit Level 2 → Level 3

## Level Goal
The password for the next level is stored in a file called –spaces in this filename– located in the home directory

- ssh bandit2@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
ls
# Lists files and directories in the current working directory.
cat -- '--spaces in this filename--'
# `--` tells the `cat` command to stop interpreting any further text as options.
# This ensures that the file named '--spaces in this filename--' is treated literally, even if it looks like a flag or has spaces/special characters.
```
<img width="851" height="169" alt="image" src="https://github.com/user-attachments/assets/c00599d1-929a-41e9-b781-5823451ef193" />

- Password got : MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
