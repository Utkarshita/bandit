# Bandit Level 0 → Level 1

## Level Goal
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
password : bandit0
```

#### Commands used
```bash
ls
# Lists files in the current directory.
cat readme
# Displays the contents of the 'readme' file.
```

<img width="687" height="167" alt="image" src="https://github.com/user-attachments/assets/d54cbf0f-859f-4240-b5e7-16be1e19f0ee" />
