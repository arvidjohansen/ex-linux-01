
# Installation procedure

Debian 11

## Velg graphical install

Select a language: `English`

Select your location: `United Kingdom`

Configure the keyboard: `Norwegian`

## Network

Hostnqame: For example  `debian-vg2-arvid` (use your own-name)

Domain name: `kuben.it`

## Users and passwords

1. First you have to select a proper password for the `root`-account. The `root`-user on a Linux system is equivalent to the Administrator-account on a Windows-system. Please choose a proper password that you will remember. 
2. Now you will create a new user account. First you have to enter the `full name` of the user, but instead just enter your desired username here, so the full name and the username is identical. I will enter `arvidj` here as the full name.
3. Enter the same for username, I will enter `arvidj` here also.
4. Make a nice password for your new user-account.

Now you will have 2 users on your system: 1 root user which has full administrator rights, and 1 user 

## Partition disks

1. Choose `Guided - use entire disk`
1. Choose the default disk that comes next `SCSI (0.....bla bla)`
2. Choose `All files in the partition (recommended for new users)
3. Choose `Finish partitioning and write changes to disk`, then `Continue`
4. Choose `Yes`to write changes to disk.

## Configure the package manager


1. Scan extra installation media? `No`
2. Debian archive mirror country: `Norway`
3. Debian archive mirror: `ftp.uio.no`
4. HTTP Proxy: `blank` (dont write anything)

## Select and install software

1. Configuring popularity contest: `No`

### Software to install

The following should be checked:

1. Debian desktop environment
2. ... GNOME
3. Standard system utilities

## Install GRUB boot loader

1. Installing GRUB boot loader to primary harddrive? `Yes`
1. Device for boot loader installation: Choose the partition that was created, usually called something like  `/dev/sda .....`

## Finish the installation

1. Reboot