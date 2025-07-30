# Bandit Level 17 → Level 18

## Level Goal
There are 2 files in the homedirectory: passwords.old and passwords.new. The password for the next level is in passwords.new and is the only line that has been changed between passwords.old and passwords.new

```bash
ssh bandit17@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
diff passwords.new passwords.old
# Show differences between the two files.
grep -wvf passwords.old passwords.new
# Print only the line from passwords.new that is NOT in passwords.old.
# -w : match whole words
# -v : invert match (show non-matching lines)
# -f : take patterns from file (passwords.old)
```

<img width="494" height="149" alt="image" src="https://github.com/user-attachments/assets/c1600493-64b7-4a5d-b3e4-228ad1e20636" />
