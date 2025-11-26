# OverTheWire Bandit - Level 0 → Level 1

**Goal**: The password for the next level is stored in a file called `readme` located in the home directory.

**Connection**
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
# Password: bandit0

Solution

bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme
The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
