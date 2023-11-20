# Linux Commands Cheat Sheet

This is a cheat sheet containing common Linux commands. Feel free to use and modify it based on your needs.

## Navigation Commands

1. `pwd`: Print working directory
2. `ls`: List files and directories
3. `cd`: Change directory
4. `mkdir`: Create a directory
5. `rmdir`: Remove an empty directory
6. `cp`: Copy files or directories
7. `mv`: Move or rename files or directories
8. `rm`: Remove files or directories
9. `touch`: Create an empty file
10. `cat`: Display the contents of a file

## File System Commands

11. `df`: Display disk space usage
12. `du`: Display file and directory space usage
13. `mount`: Mount a file system
14. `umount`: Unmount a file system
15. `ln`: Create a link to a file
16. `find`: Search for files and directories
17. `locate`: Find the location of a file
18. `grep`: Search for a pattern in files
19. `tar`: Create or extract tar archives
20. `gzip`: Compress or decompress files

## Process Management Commands

21. `ps`: Display information about running processes
22. `top`: Display real-time system statistics
23. `kill`: Terminate a process
24. `killall`: Kill processes by name
25. `pkill`: Signal processes based on their name
26. `pgrep`: Display process IDs based on their name
27. `nice`: Run a process with a specified priority
28. `renice`: Change the priority of a running process

## User and Group Commands

29. `whoami`: Display the current username
30. `id`: Display user and group information
31. `passwd`: Change user password
32. `su`: Switch user
33. `sudo`: Execute a command as a superuser
34. `useradd`: Add a new user
35. `userdel`: Delete a user
36. `groupadd`: Add a new group
37. `groupdel`: Delete a group
38. `chown`: Change file owner and group
39. `chgrp`: Change group ownership of a file

## Network Commands

40. `ifconfig`: Configure network interfaces
41. `ip`: Show/manipulate routing, devices, policy routing, and tunnels
42. `ping`: Send ICMP ECHO_REQUEST to a network host
43. `traceroute`: Print the route packets trace to network host
44. `netstat`: Display network connections, routing tables, interface statistics, masquerade connections, and multicast memberships
45. `nslookup`: Query Internet name servers interactively

## System Information Commands

46. `uname`: Display system information
47. `lsb_release`: Display Linux Standard Base information
48. `hostname`: Show or set the system's host name
49. `uptime`: Display system uptime
50. `who`: Show who is logged on
51. `w`: Display information about the users currently on the machine
52. `last`: Show a listing of last logged in users
53. `history`: Display command history
54. `free`: Display amount of free and used memory in the system
55. `ps aux`: Display detailed information about processes

## Package Management Commands

56. `apt-get`: Advanced Package Tool - Package manager for Debian/Ubuntu
57. `yum`: Yellowdog Updater Modified - Package manager for CentOS/RHEL
58. `dnf`: Dandified Yum - Package manager for Fedora
59. `zypper`: Package manager for openSUSE
60. `pacman`: Package manager for Arch Linux

## Text Processing Commands

61. `awk`: Pattern scanning and text processing language
62. `sed`: Stream editor for filtering and transforming text
63. `grep`: Search for patterns in text
64. `cut`: Remove sections from each line of a file
65. `sort`: Sort lines of text files
66. `uniq`: Report or omit repeated lines
67. `wc`: Print newline, word, and byte counts for each file
68. `head`: Output the first part of files
69. `tail`: Output the last part of files
70. `tee`: Read from standard input and write to standard output and files

## Compression and Archive Commands

71. `gzip`: Compress or decompress files
72. `tar`: Create or extract tar archives
73. `zip`: Package and compress files
74. `unzip`: Extract files from a ZIP archive
75. `bzip2`: Compress or decompress files using the BZIP2 algorithm
76. `xz`: Compress or decompress files using the XZ algorithm
77. `tar`: Create or extract tar archives
78. `zip`: Package and compress files
79. `unzip`: Extract files from a ZIP archive
80. `gzip`: Compress or decompress files
81. `zcat`: Display compressed files
82. `7z`: Compress or decompress files using the 7-Zip format
83. `rar`: Compress or decompress files using the RAR format
84. `ar`: Create or extract files from an archive

## Network Commands

85. `ifconfig`: Configure network interfaces
86. `ip`: Show/manipulate routing, devices, policy routing, and tunnels
87. `ping`: Send ICMP ECHO_REQUEST to a network host
88. `traceroute`: Print the route packets trace to network host
89. `netstat`: Display network connections, routing tables, interface statistics, masquerade connections, and multicast memberships
90. `nslookup`: Query Internet name servers interactively
91. `dig`: DNS lookup utility
92. `host`: DNS lookup utility
93. `ssh`: Secure Shell - connect to a remote server
94. `scp`: Secure Copy - copy files between hosts on a network
95. `rsync`: Remote file synchronization utility
96. `wget`: Retrieve files from the web
97. `curl`: Command-line tool for transferring data with URL syntax
98. `nc`: Netcat - networking utility for reading from and writing to network connections
99. `nmap`: Network exploration and security auditing tool

## System Control Commands

100. `shutdown`: Shutdown or restart the system
101. `reboot`: Reboot the system
102. `halt`: Halt the system
103. `poweroff`: Power off the system
104. `systemctl`: Control the systemd system and service manager
105. `service`: Run a System V init script
106. `journalctl`: Query and display messages from the journal
107. `loginctl`: introspect and interact with the state of the `systemd` manager
108. `timedatectl`: Control the system clock and its settings
109. `hostnamectl`: Query and change the system hostname and related settings
110. `localectl`: Query and change system locale and keyboard layout settings
111. `udevadm`: Control the `udev`adm administrative tool

## Text Processing Commands

112. `awk`: Pattern scanning and text processing language
113. `sed`: Stream editor for filtering and transforming text
114. `grep`: Search for patterns in text
115. `cut`: Remove sections from each line of a file
116. `sort`: Sort lines of text files
117. `uniq`: Report or omit repeated lines
118. `wc`: Print newline, word, and byte counts for each file
119. `head`: Output the first part of files
120. `tail`: Output the last part of files
121. `tee`: Read from standard input and write to standard output and files

## Disk Management Commands

122. `fdisk`: Partition table manipulator for Linux
123. `mkfs`: Build a Linux file system
124. `dd`: Convert and copy files
125. `parted`: Partition manipulation program
126. `mount`: Mount a file system
127. `umount`: Unmount a file system
128. `df`: Display disk space usage
129. `du`: Display file and directory space usage
130. `lsblk`: List information about all available block devices
131. `badblocks`: Search a device for bad blocks

## System Monitoring Commands

132. `top`: Display real-time system statistics
133. `htop`: Interactive process viewer
134. `ps`: Display information about running processes
135. `kill`: Terminate a process
136. `uptime`: Display system uptime
137. `free`: Display amount of free and used memory in the system
138. `vmstat`: Report virtual memory statistics
139. `iostat`: Report Central Processing Unit (CPU) statistics and input/output statistics for devices

## System Information Commands

140. `uname`: Display system information
141. `lsb_release`: Display Linux Standard Base information
142. `hostname`: Show or set the system's host name
143. `uptime`: Display system uptime
144. `who`: Show who is logged on
145. `w`: Display information about the users currently on the machine
146. `last`: Show a listing of last logged in users
147. `history`: Display command history
148. `lscpu`: Display information about the CPU architecture
149. `lsusb`: Display information about USB buses in the system
150. `lshw`: List hardware information
151. `lsmod`: Show the status of modules in the Linux Kernel
152. `dmidecode`: DMI table decoder
153. `inxi`: Command-line system information script
154. `hwinfo`: Hardware information tool
155. `df`: Display disk space usage
156. `du`: Display file and directory space usage

## Package Management Commands

157. `apt-get`: Advanced Package Tool - Package manager for Debian/Ubuntu
158. `dpkg`: Package manager for Debian-based systems
159. `yum`: Yellowdog Updater Modified - Package manager for CentOS/RHEL
160. `dnf`: Dandified Yum - Package manager for Fedora
161. `zypper`: Package manager for openSUSE
162. `rpm`: RPM Package Manager - Package manager for RPM-based systems
163. `pacman`: Package manager for Arch Linux

## File System Commands

164. `find`: Search for files and directories
165. `locate`: Find the location of a file
166. `grep`: Search for a pattern in files
167. `tar`: Create or extract tar archives
168. `gzip`: Compress or decompress files
169. `zip`: Package and compress files
170. `unzip`: Extract files from a ZIP archive
171. `rsync`: Remote file synchronization utility
172. `chown`: Change file owner and group
173. `chmod`: Change file permissions
174. `chgrp`: Change group ownership of a file
175. `ln`: Create a link to a file
