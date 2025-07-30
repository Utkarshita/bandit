# Bandit Level 15 → Level 16

## Level Goal
The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL/TLS encryption.

```bash
ssh bandit15@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
openssl s_client -connect localhost:30001
# Initiates a secure (SSL/TLS) connection to port 30001 on localhost using OpenSSL
```

<img width="729" height="405" alt="image" src="https://github.com/user-attachments/assets/c15e6996-1aa1-4b5f-bbd8-6106e7915fbe" />
<img width="746" height="306" alt="image" src="https://github.com/user-attachments/assets/024e48db-38bc-44cc-a694-2d97053ec9d7" />
