# Bandit Level 21 → Level 22

## Level Goal
A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.

```bash
ssh bandit21@bandit.labs.overthewire.org -p 2220
```

#### Commands used
```bash
ls
cd /etc/cron.d/
ls -l
cat cronjob_bandit22
cat /usr/bin/cronjob_bandit22.sh
cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv

```

<img width="741" height="250" alt="image" src="https://github.com/user-attachments/assets/39542fc2-86b0-42fd-9153-e4f974f36e71" />
