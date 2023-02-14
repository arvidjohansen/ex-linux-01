# ex-linux-01

## Manuell oppdatering

```shell
apt update
apt dist-upgrade
```

## Hvordan slå på automatiske oppdateringer

```shell
apt install unattended-upgrades
dpkg-reconfigure --priority=low unattended-upgrades
```




--------

## Legg til ny bruker

```shell
adduser {username}
```

## Gjøre bruker til admin (root)

```shell
usermod -aG sudo {username}
```
Merk at parametrene i kommandoene (-a og -G i dette tilfellet) ofte har en logisk betydning
>-a `add`
>-G `group`

Vi ønsker altså å modifisere (endre) en bruker med argumentene "add" og "group". 

Slike mønstre går igjen hele tiden

-------

# 25 mest brukte kommandoer
1.  `ls` - List the contents of a directory
2.  `cd` - Change the current working directory
3.  `pwd` - Print the current working directory
4.  `mkdir` - Create a new directory
5.  `rmdir` - Remove a directory
6.  `touch` - Create a new empty file
7.  `cp` - Copy files or directories
8.  `mv` - Move or rename files or directories
9.  `rm` - Remove files or directories
10. `cat` - Concatenate files and display on the screen
11. `less` - Display the contents of a file one page at a time
12. `head` - Display the first few lines of a file

13. `tail` - Display the last few lines of a file
14. `grep` - Search for patterns in files
15. `find` - Search for files that match specified criteria
16. `wc` - Count the number of lines, words, and characters in a file
17. `sort` - Sort the contents of a file
18. `uniq` - Remove or identify repeated lines in a file
19. `diff` - Compare two files and show the differences
20. `chmod` - Change file or directory permissions
21. `chown` - Change the owner of a file or directory
22. `sudo` - Run a command with superuser privileges
23. `su` - Switch to the superuser account
24. `ps` - Display information about the currently running processes
25. `kill` - Terminate a process by PID

------


# 25 til viktige  kommandoer
1.  `top` - Display real-time information about system performance and running processes
2.  `free` - Display information about memory usage
3.  `df` - Display information about disk space usage
4.  `du` - Estimate the disk space used by a file or directory
5.  `ping` - Test the reachability of a network host
6.  `traceroute` - Display the route taken by packets to a network host
7.  `netstat` - Display information about network connections
8.  `ifconfig` - Display information about network interfaces
9.  `iptables` - Configure the Linux firewall
10. `route` - Display and modify the routing table
11. `ip` - Display and manipulate IP address and routing information
12. `ssh` - Securely log into a remote machine

13. `scp` - Securely copy files between machines
14. `ftp` - Transfer files between machines using the FTP protocol
15. `sftp` - Transfer files between machines securely using the SFTP protocol
16. `rsync` - Synchronize files and directories between machines
17. `tar` - Create and extract compressed archive files
18. `gzip` - Compress or decompress files
19. `bzip2` - Compress or decompress files using the bzip2 algorithm
20. `zip` - Compress or decompress files using the ZIP format
21. `unzip` - Extract files from ZIP archive files
22. `cron` - Schedule tasks to run automatically
23. `at` - Schedule one-time tasks to run in the future
24. `systemd` - Control system services and manage system startup
25. `journalctl` - View and manage system logs managed by systemd.
