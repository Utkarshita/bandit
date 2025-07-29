# Bandit Level 11 → Level 12

## Level Goal
The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

#### Commands used
```bash
ls
cat data.txt | tr 'a-zA-Z' 'n-za-mN-ZA-M'
# Decodes ROT13 cipher from 'data.txt'. Shifts letters 13 positions in the alphabet to reveal the real text.
```

<img width="492" height="96" alt="image" src="https://github.com/user-attachments/assets/8cb7012b-f763-4666-b2b8-4963c565f46b" />

- Password got : 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
