# Bandit Level 13 → Level 14

## Level Goal
The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on

- ssh bandit13@bandit.labs.overthewire.org -p 2220

#### Commands used
```bash
ls
sort data.txt | uniq -u
# Sorts the lines in 'data.txt' to group duplicates together, then 'uniq -u' filters out only the lines that appear exactly once.
```

<img width="675" height="179" alt="image" src="https://github.com/user-attachments/assets/9637ee60-1275-4a9f-b035-e663c370b6a0" />

- Password got : 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
