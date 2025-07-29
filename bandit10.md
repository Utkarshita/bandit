# Bandit Level 10 → Level 11

## Level Goal
The password for the next level is stored in the file data.txt, which contains base64 encoded data

- ssh bandit10@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
ls
cat data.txt | base64 -d
# Reads the content of 'data.txt' and decodes it from Base64 format using 'base64 -d'.
# Used when the password is stored in encoded form.
```

<img width="814" height="196" alt="image" src="https://github.com/user-attachments/assets/5567da1c-d186-447e-9c3e-bf14b8e3d807" />

- Password got : dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
