## User & Account Management (Access Control) ##

whoami        – Shows the currently logged-in user
id            – Displays user ID (UID), group ID (GID), and groups
who           – Shows who is currently logged in
w             – Displays logged-in users and their activity
last          – Shows login history of users
lastlog       – Displays last login of all users
useradd       – Creates a new user account
usermod       – Modifies user account details
userdel       – Deletes a user account
passwd        – Changes user password
chage         – Manages password aging policies
groups        – Shows groups a user belongs to
su            – Switch user
sudo          – Execute command as another user (usually root)

## File & Directory Permissions (Critical for Security) ##

ls -l         – Lists files with permissions
stat          – Displays detailed file information
chmod         – Changes file permissions
chown         – Changes file owner
chgrp         – Changes file group
getfacl       – Displays ACL permissions
setfacl       – Sets ACL permissions

## Process & System Monitoring (Threat Detection) ##

ps aux        – Lists all running processes
top           – Real-time process monitoring
htop          – Enhanced process viewer (if installed)
uptime        – Shows system running time and load
kill          – Terminates a process by PID
killall       – Terminates processes by name
nice          – Sets process priority
renice        – Changes process priority

## Network Monitoring & Security ##

ip a          – Displays network interfaces
ip r          – Shows routing table
ifconfig      – Displays network config (legacy)
ss -tuln      – Shows listening ports and services
netstat -tuln – Displays open ports (legacy)
lsof -i       – Lists processes using network connections
ping          – Tests network connectivity
traceroute   – Tracks packet route to destination

## Firewall & Network Protection ##

iptables -L   – Lists firewall rules
iptables -A   – Adds firewall rule
iptables -D   – Deletes firewall rule
ufw status    – Displays firewall status (Ubuntu)
ufw enable    – Enables firewall
ufw allow     – Allows a service/port
ufw deny      – Blocks a service/port

## Log Analysis & Incident Investigation ##

journalctl            – Views system logs
journalctl -xe        – Shows detailed error logs
journalctl -u ssh     – Views SSH service logs
/var/log/auth.log     – Authentication logs
/var/log/syslog       – System logs
/var/log/messages     – General system messages
dmesg                 – Kernel ring buffer messages
tail -f logfile      – Live log monitoring
grep "error" logfile – Searches logs for keywords

## File Integrity & Malware Detection ##

md5sum        – Generates MD5 hash
sha256sum     – Generates SHA-256 hash
diff          – Compares two files
find / -perm -4000    – Finds SUID files
find / -perm -2000    – Finds SGID files
clamscan      – Scans files for malware (ClamAV)
freshclam     – Updates malware signatures

## Disk, Filesystem & Forensics ##

df -h         – Displays disk usage
du -sh        – Shows directory size
mount         – Mounts filesystems
umount        – Unmounts filesystems
lsblk         – Lists block devices
blkid         – Shows disk UUIDs
stat file     – Shows file metadata (timestamps)

## System Hardening & Security Checks ##

uname -a      – Displays system information
hostnamectl  – Shows hostname and OS details
chkconfig     – Manages services (RHEL-based)
systemctl    – Controls system services
sysctl -a     – Displays kernel parameters

## Archiving & Secure File Transfer ##

tar -cvf      – Creates archive
tar -xvf      – Extracts archive
gzip / gunzip – Compress / decompress files
scp           – Secure file copy over SSH
rsync         – Secure file synchronization
sftp          – Secure FTP

## Daily SOC Commands ##

watch         – Runs command repeatedly
history       – Shows command history
alias         – Creates command shortcuts
strace        – Traces system calls
ltrace        – Traces library calls


