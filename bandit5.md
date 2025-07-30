# Bandit Level 5 → Level 6

## Level Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:
- human-readable
- 1033 bytes in size
- not executable

```bash
ssh bandit5@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
cd inhere
find . -size 1033c
# Searches for files exactly 1033 bytes in size within the current directory and subdirectories.
cd maybehere07
ls
cat .file2
# Files starting with a dot are hidden by default.
```

<img width="1197" height="436" alt="image" src="https://github.com/user-attachments/assets/c4aea498-648f-4648-8b5f-e71dbf663f8b" />
