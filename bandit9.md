# Bandit Level 9 → Level 10

## Level Goal
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

- ssh bandit9@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
ls
strings data.txt | grep '='
```

<img width="857" height="831" alt="image" src="https://github.com/user-attachments/assets/d2d44d80-44f5-43f3-b450-e1bf833b47db" />
