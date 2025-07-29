# Bandit Level 13 → Level 14

## Level Goal
The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on

- ssh bandit13@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
ls
ssh -i sshkey.private bandit14@localhost -p 2220
# Logs in to bandit14 using a private key (sshkey.private) on port 2220
cat /etc/bandit_pass/bandit14
# password for bandit14 stored in the system path
```

<img width="570" height="60" alt="image" src="https://github.com/user-attachments/assets/c7621a62-71f2-4420-8c6f-0cb38660f762" />
<img width="454" height="82" alt="image" src="https://github.com/user-attachments/assets/83ef0c64-1f49-4d77-b434-93225ed716dd" />

- Password got : MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
