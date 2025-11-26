# OverTheWire Bandit – Level 1 → Level 2

**Goal**  
The password is stored in a file named `-` (single dash).

**Connection**

ssh bandit1@bandit.labs.overthewire.org -p 2220
# Password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

Solution

bandit1@bandit:~$ ls -la
-rw-r----- 1 bandit2 bandit1 33 ... -
bandit1@bandit:~$ cat ./-
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
