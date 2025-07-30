# Bandit Level 8 → Level 9

## Level Goal
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

```bash
ssh bandit8@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
sort data.txt | uniq -u
# Sorts the lines in 'data.txt' to group duplicates together, then 'uniq -u' filters out only the lines that appear exactly once.
```

<img width="675" height="118" alt="image" src="https://github.com/user-attachments/assets/f0f96255-b060-4c59-a3b9-f95185d4b1ec" />
