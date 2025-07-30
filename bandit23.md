# Bandit Level 23 → Level 24

## Level Goal
A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.
- NOTE: This level requires you to create your own first shell-script. This is a very big step and you should be proud of yourself when you beat this level!
- NOTE 2: Keep in mind that your shell script is removed once executed, so you may want to keep a copy around…

```bash
ssh bandit23@bandit.labs.overthewire.org -p 2220
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
