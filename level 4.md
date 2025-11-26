# OverTheWire Bandit – Level 4 → Level 5

**Goal**  
The password for the next level is stored in the only human-readable file in the `inhere` directory.

**Connection**
```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
# Password: 2WmrusqU3IBl9sH8o3qXU8vL7cH8pP6w

Solution

bandit4@bandit:~$ ls
inhere
bandit4@bandit:~$ cd inhere
bandit4@bandit:~/inhere$ ls
-file00  -file01  -file02  -file03  -file04  -file05  -file06  -file07  -file08  -file09
bandit4@bandit:~/inhere$ file ./*
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text   # ← ده الوحيد اللي human-readable
./-file08: data
./-file09: data

bandit4@bandit:~/inhere$ cat ./-file07
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
