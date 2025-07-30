# Bandit Level 14 → Level 15

## Level Goal
The password for the next level can be retrieved by submitting the password of the current level to port 30000 on localhost.

```bash
ssh bandit14@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
nc localhost 30000
# Connects to port 30000 on your own machine (localhost) using netcat to read incoming data
```

<img width="561" height="75" alt="image" src="https://github.com/user-attachments/assets/012a687a-06c8-48b3-9e10-b9512ccbcec5" />
