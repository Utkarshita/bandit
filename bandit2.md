# Bandit Level 2 → Level 3

## Level Goal
The password for the next level is stored in a file called –spaces in this filename– located in the home directory

```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
# Lists files and directories in the current working directory.
cat -- '--spaces in this filename--'
# `--` tells the `cat` command to stop interpreting any further text as options.
# This ensures that the file named '--spaces in this filename--' is treated literally, even if it looks like a flag or has spaces/special characters.
```

<img width="577" height="115" alt="image" src="https://github.com/user-attachments/assets/808bff00-0f3f-4ed4-b297-ba90f2bb5210" />
