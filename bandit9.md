# Bandit Level 9 → Level 10

## Level Goal
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

```bash
ssh bandit9@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
strings data.txt | grep '='
# 'strings' extracts all readable text from the binary file 'data.txt'. The output is piped to 'grep', which searches for lines containing '='.
```

<img width="857" height="739" alt="image" src="https://github.com/user-attachments/assets/22bf3d1b-27db-45f0-86c3-c8b9c3c32a9a" />
