# Bandit Level 20 → Level 21

## Level Goal
There is a setuid binary in the homedirectory that does the following: it makes a connection to localhost on the port you specify as a commandline argument. It then reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21).
```bash
ssh bandit20@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
ls -l
./bandit20-do
# Running without arguments shows usage instructions (acts as a helper tool).
./bandit20-do id
./bandit20-do cat /etc/bandit_pass/bandit20

```

<img width="714" height="140" alt="image" src="https://github.com/user-attachments/assets/b3d61db5-a085-4088-8692-cd270f7e2ac8" />

