# OverTheWire Bandit – Level 10 → Level 11

**Goal**
The password for the next level is stored in the file `data.txt`, which contains **base64-encoded data.


**Connection**
ssh bandit10@bandit.labs.overthewire.org -p 2220
# Password: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey


**Solution**
bandit10@bandit:~$ base64 -d data.txt
The password is **dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr**
