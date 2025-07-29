# Bandit Level 5 → Level 6

## Level Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:
- human-readable
- 1033 bytes in size
- not executable
---
- ssh bandit5@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
cd inhere
find . -size 1033c
cd maybehere07
ls
cat .file2

```

<img width="1197" height="471" alt="image" src="https://github.com/user-attachments/assets/6c0e7e90-ff41-49cf-b0de-f498965e6204" />
