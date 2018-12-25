# SSHacKali
This tool hacks Kali machines that uses the default password (toor) for the root user account.
The tool can be used to enforce changing the default Kali password for root users.

## Getting Started
This tool does the following:
 - takes an IP (example: 192.168.0.0) and search the the subnet (example: 192.168.0.0 - 192.168.0.255) for SSH open ports.
 - uses the default root/toor (user/password) combination.
 - takes a username to make a new account with it on the hacked machine.
 - takes a new password to change the hacked user password, and it uses the same password for the new user account.
  
### Installing
After downloading the files (SSHack and SSHackSup)
- Give SSHack execution permission:
```
sudo chmod 755 SSHacKali
```
- Give SSHackSup execution permission:
```
sudo chmod 755 SSHacKaliSub
```

### User Guide
Execute ./SSHacKali then follow the instructions. 
```
./SSHacKali
```
