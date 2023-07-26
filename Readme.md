# Linux Filesystem
* Linux follows a hierarchical file system.
* Any file or directory starts from "/" which is root users home directory.
* under root user home directory ("/") there are different directories.
1. /bin: It contains user binaries. It generally contains common linux commands which are executed in single user mode such as ls, grep, ping etc.
2. /sbin: It contains system binaries. Generally it is used by the system administrators.
3. /etc: It contains Configuration files. The configuration files of any package installed are present in this folder.
4. /dev: It contains Device files. Any new device like usb, harddisk attached to the system has its device file created in this folder.
5. /proc: It contains Process information. It is a pseudo file system. If the system is rebooted, the data in /proc is lost.
6. /var: It contains variable files. It means the log files of databases etc. The content of the files that are expected to grow are found in this directory.
7. /tmp: It contains Temporary files. Files present in this directory are lost when system is rebooted.
8. /usr: It contains user programs.
9. /home: Home directory for all the users.
10. /boot: It contains boot loader files.
11. /lib: It contains system libraries.
12. /opt: It contains optional add-on apps.
13. /mnt: It is used to mount file system.
14. /media: It contains temporary mount for removable devices like floppy etc.
15. /srv: It contains server specific services related data.
