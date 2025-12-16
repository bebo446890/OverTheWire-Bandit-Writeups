# OverTheWire Bandit – Level 9 → Level 10

**Goal**
The password for the next level is stored in the file `data.txt` in one of the few human-readable strings, preceded by several '=' characters.


**Connection**
ssh bandit9@bandit.labs.overthewire.org -p 2220
# Password: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM


**Solution**
bandit9@bandit:~$ strings data.txt | grep "=="
========== the
========== password
E========== is
5========== **FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey**
