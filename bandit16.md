# Bandit Level 16 → Level 17

## Level Goal
The credentials for the next level can be retrieved by submitting the password of the current level to a port on localhost in the range 31000 to 32000. First find out which of these ports have a server listening on them. Then find out which of those speak SSL/TLS and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.

```bash
ssh bandit16@bandit.labs.overthewire.org -p 2220
```
#### Commands used
```bash
nmap localhost -p 31000-32000
# Scan for open ports in the given range.
nmap localhost -p 31046,31518,31691,31790,31960 -sV -T4
# Check service versions on suspicious open ports.
echo kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx | openssl s_client -connect localhost:31790 -ign_eof
# Connect to the SSL-enabled port and send the password to retrieve a private key.
mktemp -d
cd /tmp/tmp.wFBG6Rer81
mkdir rsa
cd rsa
nano rsafile
# Paste the private key received into 'rsafile'
ls -l
chomd 600 rsafile
# Set proper permissions for the private key
ssh -i rsafile bandit17@localhost -p 2220
# SSH into the next level using the private key.
cat /etc/bandit_pass/bandit17
#to see password for next level
```

<img width="940" height="804" alt="image" src="https://github.com/user-attachments/assets/4cd88cb7-8dd5-4b21-b4c6-da5dd75a7b9c" />
<img width="764" height="408" alt="image" src="https://github.com/user-attachments/assets/0c527571-110e-4ab3-92b6-f3deafaa6f73" />
<img width="595" height="98" alt="image" src="https://github.com/user-attachments/assets/23ccc32f-c770-41c9-a2a2-e692f02876c9" />


