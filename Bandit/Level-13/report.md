# Objetive
- The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Look at the commands that logged you into previous bandit levels, and find out how to use the key for this level.
## Solution
- At first I didn't know how to use the private key to connect to the server, then I discovered that by copying the file to my local PC and using it to connect via SSH as if I had a local password, ssh -i "file" allowed me to access bandit14 
- MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
## Commands used

- ssh -i 
- chmod 600
- cat  
- cd etc/bandit_pass/bandit14
- ls
- cd
