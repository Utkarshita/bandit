# Bandit Level 3 → Level 4

## Level Goal
The password for the next level is stored in a hidden file in the inhere directory.

```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
cd inhere
ls -al
# Lists all files, including hidden ones, with detailed info
cat ...Hiding-From-You
# Displays the content of the file named '...Hiding-From-You'.
```

<img width="1044" height="394" alt="image" src="https://github.com/user-attachments/assets/b2e41df7-f6aa-4486-b9ce-50139bd3b715" />
