# Bandit Level 19 → Level 20

## Level Goal
To gain access to the next level, you should use the setuid binary in the homedirectory. Execute it without arguments to find out how to use it. The password for this level can be found in the usual place (/etc/bandit_pass), after you have used the setuid binary.

```bash
ssh bandit19@bandit.labs.overthewire.org -p 2220
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

