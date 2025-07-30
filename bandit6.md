# Bandit Level 6 → Level 7

## Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties:
- owned by user bandit7
- owned by group bandit6
- 33 bytes in size

```bash
ssh bandit6@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
# '2>/dev/null' hides permission-denied error messages for cleaner output.
cd /var/lib/dpkg/info/
cat bandit7.password
```

<img width="1250" height="173" alt="image" src="https://github.com/user-attachments/assets/581bd5da-26f5-4f91-91f1-71d78f41a0cc" />
