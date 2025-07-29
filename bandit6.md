# Bandit Level 6 → Level 7

## Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties:
- owned by user bandit7
- owned by group bandit6
- 33 bytes in size
---
- ssh bandit6@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cd /var/lib/dpkg/info/
cat bandit7.password
```

<img width="1182" height="240" alt="image" src="https://github.com/user-attachments/assets/60cd422c-2278-40fa-9565-459eae9688ca" />

