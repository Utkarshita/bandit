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

<img width="1191" height="541" alt="image" src="https://github.com/user-attachments/assets/2005b65a-c805-41c9-a370-97ccc5967903" />
