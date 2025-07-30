# Bandit Level 7 → Level 8

## Level Goal
The password for the next level is stored in the file data.txt next to the word millionth

```bash
ssh bandit7@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
cat data.txt | grep 'millionth'
# Reads the content of 'data.txt' using 'cat', then pipes it to 'grep' to search for the line containing the word 'millionth'.
```

<img width="819" height="318" alt="image" src="https://github.com/user-attachments/assets/86a0aefa-e842-4e4d-be08-3452d27a6c47" />
<img width="587" height="47" alt="image" src="https://github.com/user-attachments/assets/ff771ef5-2e4c-4d4c-a24d-c570fa50265c" />



