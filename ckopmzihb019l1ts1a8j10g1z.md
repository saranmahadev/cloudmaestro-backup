## Linux Commands 101

---
## adduser/addgroup
Allows us to add users and groups to the system

### agetty 
A program which manages physical or virtual terminals and is invoked by init. When it detects a connection, it opens a tty port, asks for a user’s login name and calls up the /bin/login command.

### alias 
Creates aliases to a Linux command. Its temporary for a session, you can make it permanent by adding them to ~/.bashrc file.

### anacron 
Used to run commands periodically with a frequency defined in days, weeks and months (Similar to CRON where CRON is appropriate for servers and ACRON is for desktop/laptop machines). 

>Remember: CRON is a daemon where anacron is not a daemon

### apropos
Used to search and display a short man page description of a command/program.

### apt
A higher-level package manager.

### apt-get 
A Front-end package manager.

### aptitude
A powerful text-based interface to the package management system.

### arch 
Displays machine architecture or hardware name.

### arp
Maps IP network addresses of a network neighbor with the hardware (MAC) addresses in an IPv4 network.

### at [An alternative to cron and anacron]
Schedule tasks to run in a future time.

### atq
View jobs in **at command** queue.

### atrm
Used to remove/deletes **at command** jobs.

### awk
A powerful programming language created for text processing and generally used as a data extraction and reporting tool.

### batch
Used to schedule tasks to run a future time, similar to the at command.

### basename
Prints the name of a file stripping of directories in the absolute path.

### bc
Powerful and Arbitrary Precision CLI Calculator.

### bg
Sends a process to the background.

### bzip2
Used to compress or decompress a file.

### cal
Prints the Calendar.

### chrgrp
Changes the group ownership of a file.

### chmod
Changes File access permissions.

### chown
Changes the user/group ownership of a file.

### cksum
Display the CRC checksum and byte count of an input file.

### clear
Clears the Terminal.

### cmp 
Compares between bytes of two files.

### comm
Compares to two sorted files line-by-line.

### cp
Used to Copy files and folders.

### date 
Displays the system date and time.

### dd
Used for copying files, converting and formatting according to flags provided.

### df
Shows file system disk space usage.

### diff
Compare two files line by line.

### dir 
Lists the contents of the directory.

### dmidecode 
A tool for retrieving hardware information of any Linux system.

### du
Show disk space usage of files present in a directory as well as its sub-directories.

### echo
Prints a text of line provided to it.

### eject
Ejects removable media such as DVD/CD ROM or floppy disk from the system.

### env
Lists all the current environment variables and used to set them as well.

### exit
Used to exit a Shell.

### expr
Used to calculate an expression.

### factor
Shows the Prime factors of the number.

### find
Search for files in a directory as well as its sub-directories.

### free
Shows the system memory usage.

### grep
Searches for a specified pattern in a file or files.

### group
Displays all the names of groups a user is a part of.

### Gzip
Helps to compress a file, replaces it with one having a .gz extension.

### Gunzip 
Expands or restores files compressed with gzip command.

### head 
Shows first lines (10 lines by default) of the specified file or stdin to the screen.

### history
Shows previously used commands or to get info about command executed by a user.

### hostname
Used to print or set system hostname in Linux.

### hostnamectl
Used to print or modify the system hostname and any related settings.

### hwclock
A tool for managing the system hardware clock; read or set the hardware clock.

### hwinfo
Used to probe for the hardware present in a Linux system.

### id
Shows user and group information for the current user or specified username.

### ifconfig
Used to configure a systems network interfaces.

### ionice
Used to set or view process I/O scheduling class and priority of the specified process.

### iostat
Used to show CPU and input/output statistics for devices and partitions.

### ip
Used to display or manage routing, devices, policy routing and tunnels.

### iptables
For managing incoming and outgoing traffic via a set of configurable table rules.

### iw
Used to manage wireless devices and their configuration.

### iwlist 
Displays detailed wireless information from a wireless interface.

### kill
Used to kill a process using its PID by sending a signal to it.

### killall
Used to kill a process by its name.

### kmod
Used to manage Linux kernel modules.

### last
Displays a listing of last logged in users.

### ln
Used to create a soft link between files.

### locate
Used to find a file by name. 

### login
Used to create a new session with the system.

### ls
Used to list contents of a directory.

### lshw
A minimal tool to get detailed information on the hardware configuration of the machine.

>Remember: Invoke it with superuser privileges to get a comprehensive information.

### lscpu
Displays system’s CPU architecture information.

### lsof
Displays information related to files opened by processes.

### lsusb
Shows information about USB buses in the system and the devices connected to them.

### man
Used to view the on-line reference manual pages for commands/programs.

### md5sum
Used to compute and print the MD5 message digest of a file. 

>Remember:  If run without arguments, debsums checks every file on your system against the stock md5sum files

### mkdir
Creates one or more folders.

### more
Enables you to view through relatively lengthy text files one screenful at a time.

### mv
Used to move a file or folder and also used to rename a file or folder.

### nano
A Small and Friendly Text Editor

### nc (or) netcat
Used for performing any operation relating to TCP, UDP, or UNIX-domain sockets.

### netstat
Displays useful information concerning the Linux networking subsystem like
- network connections, 
- routing tables, 
- interface statistics, 
- masquerade connections, 
- and multicast memberships.

### nice
Used to show or change the nice value of a running program.

### nmap
A popular and powerful open source tool for network scanning and security auditing.

### nproc 
Shows the number of processing units present to the current process. 

### openssl
A command line tool for using the different cryptography operations of OpenSSL’s crypto library from the shell. 

### passwd
Used to create/update passwords.

### pid
Displays the process ID of a running program/command.

### ping
Used to determine connectivity between hosts on a network.

### ps
Shows useful information about active processes running on a system.

### pstree
Displays running processes as a tree which is rooted at either PID or init if PID is omitted.

### pwd
Displays the name of current/working directory.

### rdiff 
A powerful local/remote incremental backup script written in Python.

### reboot
Used to halt, power-off or reboot a system.

### rename
Used to rename many files at once.

### rm
Used to remove files or directories.

### rmdir
Helps to delete/remove empty directories.

### scp
Enables you to securely copy files between hosts on a network.

### shutdown
Schedules a time for the system to be powered down.

### sleep
Used to delay or pause.

### sort 
Used to sort lines of text in the specified file(s) or from stdin.

### split
Used to split a large file into small parts.

### ssh
An application for remotely accessing and running commands on a remote machine.

### stat
Used to show a file or file system status.

### su
Used to switch to another user ID or become root during a login session.

### sudo
Allows a permitted system user to run a command as root or another user.

### sum
Used to show the checksum and block counts for each each specified file on the command line.

### tac
Concatenates and displays files in reverse. 

### tail
Used to display the last lines (10 lines by default) of each file to standard output.

### talk
Used to talk to another system/network user. 

### tar
A most powerful utility for archiving files.

### tee
Used to read from standard input and prints to standard output.

### tree
A tiny, cross-platform command-line program used to recursively list or display the content of a directory in a tree-like format.

### time
Runs programs and summarizes system resource usage.

### top
Displays all processes on a Linux system in regards to memory and CPU usage and provides a dynamic real-time view of a running system.

### touch
Changes file timestamps

### tr
A useful utility used to translate or delete characters from stdin, and write the result to stdout or send to a file.

### uname
Displays system information such as operating system, network node hostname kernel name, version and release etc.

### uniq
Displays or omits repeated lines from input.

### uptime
Shows how long the system has been running.

### users
Shows the user names of users currently logged in to the current host.

### vim
Used to edit all kinds of plain text and program files.

### w
Displays system uptime, load averages and information about the users currently on the machine, and what they are doing.

### wall
Used to send/display a message to all users on the system.

### watch
Runs a program repeatedly while displaying its output on fullscreen.

### wc
Used to display newline, word, and byte counts for each file specified, and a total for many files.

### wget
A simple utility used to download files from the Web in a non-interactive way.

### whatis
Searches and shows a short or one-line manual page descriptions of the provided command name

### which
Displays the absolute path of the files which would be executed in the current environment.

### who
Shows information about users who are currently logged in.

### whereis
Helps us locate the binary, source and manual files for commands.

### xargs
A useful utility for reading items from the standard input, delimited by blanks or newlines, and executes the entered command.

### yes
Used to display a string repeatedly until when terminated or killed.

### zcmp and zdiff
A minimal utilities used to compare compressed files.

### zip
A simple and easy-to-use utility used to package and compress files.

### zz
Offers quick access to files and directories 

and there more commands. Comment Below the commands that are left out...😉

---

Reference : tecmint.com






































