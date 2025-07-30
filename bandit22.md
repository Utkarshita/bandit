# Bandit Level 22 → Level 23

## Level Goal
A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.

NOTE: Looking at shell scripts written by other people is a very useful skill. The script for this level is intentionally made easy to read. If you are having problems understanding what it does, try executing it to see the debug information it prints.

```bash
ssh bandit22@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
cd /etc/cron.d/
ls -l
cat cronjob_bandit23
cat /usr/bin/cronjob_bandit23.sh
echo I am user bandit23 | md5sum | cut -d ' ' -f 1
cat /tmp/8ca319486bfbbc3663ea0fbe81326349

```

<img width="755" height="480" alt="image" src="https://github.com/user-attachments/assets/4e1cb85c-bfe2-4281-b61a-d14e11ad51c5" />
