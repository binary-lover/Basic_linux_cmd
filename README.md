# Top 200 Linux Commands Cheat Sheet

This is a cheat sheet containing the top 100 Linux commands that every user or system administrator should be familiar with.

```markdown

## Navigation Commands

1. `pwd`: Print working directory
2. `ls`: List files and directories
3. `cd`: Change directory
4. `mkdir`: Create a directory
5. `cp`: Copy files or directories
6. `mv`: Move or rename files or directories
7. `rm`: Remove files or directories
8. `touch`: Create an empty file
9. `cat`: Display the contents of a file
10. `man`: Display the manual for a command

## File System Commands

11. `df`: Display disk space usage
12. `du`: Display file and directory space usage
13. `mount`: Mount a file system
14. `umount`: Unmount a file system
15. `ln`: Create a link to a file
16. `find`: Search for files and directories
17. `grep`: Search for a pattern in files
18. `tar`: Create or extract tar archives
19. `gzip`: Compress or decompress files
20. `chmod`: Change file permissions

## Process Management Commands

21. `ps`: Display information about running processes
22. `top`: Display real-time system statistics
23. `kill`: Terminate a process
24. `killall`: Kill processes by name
25. `pkill`: Signal processes based on their name
26. `pgrep`: Display process IDs based on their name
27. `nice`: Run a process with a specified priority
28. `renice`: Change the priority of a running process
29. `jobs`: Display status of jobs in the background
30. `bg`: Put a job in the background

## User and Group Commands

31. `whoami`: Display the current username
32. `id`: Display user and group information
33. `passwd`: Change user password
34. `su`: Switch user
35. `sudo`: Execute a command as a superuser
36. `useradd`: Add a new user
37. `userdel`: Delete a user
38. `groupadd`: Add a new group
39. `groupdel`: Delete a group
40. `chown`: Change file owner and group

## Network Commands

41. `ifconfig`: Configure network interfaces
42. `ip`: Show/manipulate routing, devices, policy routing, and tunnels
43. `ping`: Send ICMP ECHO_REQUEST to a network host
44. `traceroute`: Print the route packets trace to network host
45. `netstat`: Display network connections, routing tables, interface statistics, masquerade connections, and multicast memberships
46. `nslookup`: Query Internet name servers interactively
47. `dig`: DNS lookup utility
48. `host`: DNS lookup utility
49. `ssh`: Secure Shell - connect to a remote server
50. `scp`: Secure Copy - copy files between hosts on a network

## System Information Commands

51. `uname`: Display system information
52. `lsb_release`: Display Linux Standard Base information
53. `hostname`: Show or set the system's host name
54. `uptime`: Display system uptime
55. `who`: Show who is logged on
56. `w`: Display information about the users currently on the machine
57. `last`: Show a listing of last logged in users
58. `history`: Display command history
59. `lscpu`: Display information about the CPU architecture
60. `lsusb`: Display information about USB buses in the system

## Package Management Commands

61. `apt-get`: Advanced Package Tool - Package manager for Debian/Ubuntu
62. `dpkg`: Package manager for Debian-based systems
63. `yum`: Yellowdog Updater Modified - Package manager for CentOS/RHEL
64. `dnf`: Dandified Yum - Package manager for Fedora
65. `zypper`: Package manager for openSUSE
66. `rpm`: RPM Package Manager - Package manager for RPM-based systems
67. `pacman`: Package manager for Arch Linux
68. `apt`: Advanced Package Tool - Package manager for Debian/Ubuntu (alternative)
69. `yum`: Yellowdog Updater Modified - Package manager for CentOS/RHEL (alternative)
70. `dnf`: Dandified Yum - Package manager for Fedora (alternative)

## Text Processing Commands

71. `awk`: Pattern scanning and text processing language
72. `sed`: Stream editor for filtering and transforming text
73. `grep`: Search for patterns in text
74. `cut`: Remove sections from each line of a file
75. `sort`: Sort lines of text files
76. `uniq`: Report or omit repeated lines
77. `wc`: Print newline, word, and byte counts for each file
78. `head`: Output the first part of files
79. `tail`: Output the last part of files
80. `tee`: Read from standard input and write to standard output and files

## Compression and Archive Commands

81. `gzip`: Compress or decompress files
82. `tar`: Create or extract tar archives
83. `zip`: Package and compress files
84. `unzip`: Extract files from a ZIP archive
85. `bzip2`: Compress or decompress files using the BZIP2 algorithm
86. `xz`: Compress or decompress files using the XZ algorithm
87. `tar`: Create or extract tar archives (alternative)
88. `zip`: Package and compress files (alternative)
89. `unzip`: Extract files from a ZIP archive (alternative)
90. `bzip2`: Compress or decompress files using the BZIP2 algorithm (alternative)

## System Control Commands

91. `shutdown`: Shutdown or restart the system
92. `reboot`: Reboot the system
93. `halt`: Halt the system
94. `poweroff`: Power off the system
95. `systemctl`: Control the systemd system and service manager
96. `service`: Run a System V init script
97. `journalctl`: Query and display messages from the journal
98. `loginctl`: introspect and interact with the state of the `systemd` manager
99. `timedatectl`: Control the system clock and its settings
100. `hostnamectl`: Query and change the system hostname and related settings
Certainly! Here's a list of Linux commands starting from 101 to 200, with each command not mentioned in the previous list (1 to 100):


# Additional 100 Linux Commands (101-200)

## File System Commands

101. `truncate`: Shrink or extend the size of a file
102. `chgrp`: Change group ownership of a file
103. `mktemp`: Create a temporary file or directory
104. `filefrag`: Report on fragmentation in files
105. `readlink`: Display value of a symbolic link or canonical file name
106. `realpath`: Print the resolved path of specified files or directories
107. `basename`: Strip directory and suffix from filenames
108. `dirname`: Strip the last component from file name
109. `lsmod`: Show the status of modules in the Linux Kernel
110. `modprobe`: Add or remove modules from the Linux Kernel

## Process Management Commands

111. `systemd-cgtop`: Display cgroup resource usage
112. `bg`: Run jobs in the background
113. `fg`: Bring a background job to the foreground
114. `disown`: Remove jobs from the shell's job table
115. `nohup`: Run a command immune to hangups
116. `jobs`: Display status of jobs in the background
117. `nice`: Run a command with a specified priority
118. `batch`: Schedule commands to be executed in a batch queue
119. `cron`: Schedule periodic background tasks
120. `crontab`: Manage cron jobs for users

## System Information Commands

121. `dmsetup`: Device-mapper setup
122. `lsblk`: List information about all available block devices
123. `numactl`: Control NUMA policy for processes or shared memory
124. `lscpu`: Display information about the CPU architecture
125. `lsusb`: Display information about USB buses in the system
126. `lspci`: List all PCI devices
127. `lsmod`: Show the status of modules in the Linux Kernel
128. `uname -r`: Display the Linux kernel release
129. `uname -a`: Display all system information
130. `uname -m`: Display the machine hardware name

## Networking Commands

131. `ethtool`: Query or control network driver and hardware settings
132. `iftop`: Display bandwidth usage on an interface
133. `route`: Show or manipulate the IP routing table
134. `mtr`: Network diagnostic tool combining ping and traceroute
135. `traceroute6`: Print the route IPv6 packets will take to a network node
136. `ifup`: Bring a network interface up
137. `ifdown`: Take a network interface down
138. `hostname`: Show or set the system's host name
139. `resolvconf`: Manage nameserver information
140. `nslookup`: Query Internet name servers interactively

## User and Group Commands

141. `gpasswd`: Administer /etc/group and /etc/gshadow
142. `newgrp`: Change to a new group
143. `sg`: Execute a command as another group
144. `setfacl`: Set file access control lists
145. `getfacl`: Get file access control lists
146. `w`: Display information about the users currently on the machine
147. `who`: Show who is logged on
148. `users`: List the login names of users currently on the host
149. `lastlog`: Display the last login information of all users
150. `chpasswd`: Update passwords in batch mode

## Package Management Commands

151. `zypper`: Package manager for openSUSE
152. `pacman -S`: Install packages in Arch Linux
153. `pacman -R`: Remove packages in Arch Linux
154. `pacman -Syu`: Update all packages in Arch Linux
155. `zypper`: Package manager for openSUSE
156. `rpm`: RPM Package Manager - Package manager for RPM-based systems
157. `yum`: Yellowdog Updater Modified - Package manager for CentOS/RHEL
158. `dnf`: Dandified Yum - Package manager for Fedora
159. `zypper`: Package manager for openSUSE
160. `apt-file search`: Search for files in packages

## Text Processing Commands

161. `csplit`: Split a file into sections determined by context lines
162. `awk -F`: Specify a field separator
163. `tac`: Concatenate and print files in reverse
164. `fold`: Wrap each input line to fit in specified width
165. `fmt`: Simple optimal text formatter
166. `strings`: Display printable strings in binary files
167. `cmp`: Compare two files byte by byte
168. `sdiff`: Merge two files interactively
169. `hexdump`: Display file content in hexadecimal
170. `cut -d`: Specify a delimiter for the `cut` command

## Compression and Archive Commands

171. `xzcat`: Decompress .xz files
172. `lzma`: Compress or decompress files using the LZMA algorithm
173. `lzop`: Compress or decompress files using the LZO algorithm
174. `lz4`: Fast compression algorithm
175. `zipinfo`: List detailed information about a ZIP archive
176. `unrar`: Extract files from RAR archives
177. `unace`: Extract files from ACE archives
178. `7za`: Command-line version of 7-Zip
179. `unar`: Extract files from any archive format
180. `ar`: Create, modify, and extract from archives

## System Control Commands

181. `shutdown`: Shutdown or restart the system
182. `reboot`: Reboot the system
183. `halt`: Halt the system
184. `poweroff`: Power off the system
185. `systemctl`: Control the systemd system and service manager
186. `systemd-analyze`: Analyze and debug system manager
187. `systemd-cgtop`: Display cgroup resource usage
188.

 `systemd-run`: Run programs in transient scope
189. `systemd-hwdb`: Hardware database management tool
190. `loginctl`: Introspect and interact with the state of the `systemd` manager

## Miscellaneous Commands

191. `ascii`: Display ASCII character set
192. `rev`: Reverse lines of a file
193. `yes`: Output a string repeatedly
194. `cal`: Display a calendar
195. `nc`: Netcat - networking utility for reading/writing network connections
196. `tree`: List contents of directories in a tree-like format
197. `tput`: Set terminal-dependent capabilities
198. `gpg`: GNU Privacy Guard - encryption and signing tool
199. `curl`: Command-line tool for transferring data with URL syntax
200. `wget`: Non-interactive network downloader

Feel free to use and modify this extended list based on your needs. Add or remove commands and sections as necessary.
```
