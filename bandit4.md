# Bandit Level 4 → Level 5

## Level Goal
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

- ssh bandit4@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
ls
cd inhere
find . -type f | xargs file
cat ./-file07
```

<img width="1163" height="524" alt="image" src="https://github.com/user-attachments/assets/fb6e9699-c9c1-4c25-bb35-64b5a7d3c73e" />

