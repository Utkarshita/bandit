# Bandit Level 20 → Level 21

## Level Goal
There is a setuid binary in the homedirectory that does the following: it makes a connection to localhost on the port you specify as a commandline argument. It then reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21).
```bash
ssh bandit20@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls (terminal 1)
./suconnect (terminal 1)
Nc -lvp 12345 (terminal 2)
# This starts a netcat server listening on port 12345.
./suconnect 12345 (terminal 1)
# This runs the binary and tells it to connect to port 12345.
# password of current level (terminal 2)
```

<img width="629" height="191" alt="image" src="https://github.com/user-attachments/assets/9b7e4d52-39b1-4fe6-9521-07c4eaeb4948" />
<img width="353" height="127" alt="image" src="https://github.com/user-attachments/assets/7903a204-eda9-40ae-acb9-f168c8e6a54b" />
