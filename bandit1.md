# Bandit Level 1 → Level 2

## Level Goal
The password for the next level is stored in a file called - located in the home directory

```bash
- ssh bandit1@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
# Lists files and directories in the current directory.
cat ./-
# Displays the contents of a file literally named '-'.
# './' is used to clarify that '-' is a filename, not an option.
```

<img width="367" height="68" alt="image" src="https://github.com/user-attachments/assets/63c25322-df1c-454f-a677-fcebadfdc014" />


