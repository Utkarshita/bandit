# Bandit Level 4 → Level 5

## Level Goal
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
cd inhere
find . -type f | xargs file
# Finds all regular files in the current directory and subdirectories, then checks their file type using the `file` command.
cat ./-file07
# The './' is used because the filename starts with a dash, which could be confused as an option.
```

<img width="1191" height="483" alt="image" src="https://github.com/user-attachments/assets/0a3a4a03-643c-444f-80d1-a2503eea004a" />
