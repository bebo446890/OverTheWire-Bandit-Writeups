# OverTheWire Bandit – Level 3 → Level 4

**Goal**  
The password is hidden in a hidden file inside the `inhere` directory.

**Connection**
```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
# Password: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

Solution

bandit3@bandit:~$ ls
inhere
bandit3@bandit:~$ cd inhere
bandit3@bandit:~/inhere$ ls -la
total 20
drwxr-xr-x 2 root    root    4096 Oct 14 09:26 .
drwxr-xr-x 3 root    root    4096 Oct 14 09:26 ..
-rw-r----- 1 bandit4 bandit3   33 Oct 14 09:26 .hidden

bandit3@bandit:~/inhere$ cat .hidden
2WmrusqU3IBl9sH8o3qXU8vL7cH8pP6w
