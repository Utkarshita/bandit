# Bandit Level 14 → Level 15

## Level Goal
The password for the next level can be retrieved by submitting the password of the current level to port 30000 on localhost.

- ssh bandit14@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
nc localhost 30000
# Connects to port 30000 on your own machine (localhost) using netcat to read incoming data
```

<img width="561" height="134" alt="image" src="https://github.com/user-attachments/assets/65f71535-558e-4da8-8f05-97398d4caa43" />

- Password got : 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
