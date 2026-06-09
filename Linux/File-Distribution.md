# Linux File Hierarchy Structure (FHS)

## Overview
- The Linux File Hierarchy Strudture defines the organisations of directories and files in a Linux system.
- Unlike Windows, Linux uses a single root directory (/) from which all other directories branch out.

## Root Directory (/)
- Top-level directorry of the Linux filesystem
- All files and directories originate from this location.

## Important Directories

1. /bin
- Contains essential user commands
- Accessible by all users
Eg: ls
    cp
    mv
    cat

2. /boot
- Files required during system startup.
- Contains bootloader files and Linux kernel.
Eg: vmlinuz
    grub/

3.  /dev
- Stores device files
- Represents hardware devices as files.
Eg: /dev/sda
    /dev/tty
    /dev/null

4. /etc
- Contains system-wide configuration files.
- No executable binaries.

5. /home
- Personal directories of users

6. /lib
- Essential shared libraries needed by binaries in /bin and /sbin

7. /media
- Automatically mounted removable media

8. /mnt
- Temporary mount point for filesystems

9. /opt
- Optional third-party software packages

10. /proc
- Virtual filesystem containing process and kernel information
  
11. /root
- Home directory of the root user.

12. /run
- Stores runtime information of running processes.

13. /sbin
- Essential system administration commands.
  
14. /srv
- Data served by system services
Eg: Web server files
    FTP server files
  
15. /sys
- Virtual filesystem providing hardware and kernel information.

16. /tmp
- Temporary files
- Often cleared on reboot
  
17. /var
- Variable data that changes frequently

18. /usr
- User application and utilities


