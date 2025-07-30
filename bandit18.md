# Bandit Level 18 → Level 19

## Level Goal
The password for the next level is stored in a file readme in the homedirectory. Unfortunately, someone has modified .bashrc to log you out when you log in with SSH.

```bash
ssh bandit18@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
cat /etc/shells
# Lists available valid shells on the system. Useful to find alternative shells like /bin/sh or /bin/bash.
ssh bandit18@bandit.labs.overthewire.org -p 2220 -t /bin/sh
# -t forces pseudo-terminal allocation.
# /bin/sh is specified as the shell to bypass restricted login shell.
ls
cat readme
```

<img width="660" height="633" alt="image" src="https://github.com/user-attachments/assets/5bd72eec-6696-45e1-94c8-ce29ce6e21a3" />
