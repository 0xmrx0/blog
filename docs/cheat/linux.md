# Linux Enum

> I am creating a simple Quick recon check list for linux environment for Post Exploitation.

---

## Ready to Start

```bash
whoami
id
groups
sudo -l
sudo -v
crontab -l
cat /etc/crontab
ls -la /
```

---

## System & Identity

```bash
id                              # User's identity information
hostname                        # Host Computer Details
whoami                          # who are you !
uname -a                        # Display system information
sudo -l                         # which files you can run as root
sudo -V                         # sudo version Exploit
cat /etc/os-release             # Os Details for kernal Exploit
uptime                          # Shows how long the system has been running
last -n 5                       # shows the login history of last 5 users
cat /etc/passwd | grep -i 'sh$' # list users
```
