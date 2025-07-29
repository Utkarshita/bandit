# Bandit Level 8 → Level 9

## Level Goal
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

- ssh bandit8@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
ls
cat data.txt | uniq -u
```

<img width="675" height="179" alt="image" src="https://github.com/user-attachments/assets/9637ee60-1275-4a9f-b035-e663c370b6a0" />
