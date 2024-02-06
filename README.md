# All Linux commend <p align="left">
<a href="https://www.linux.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" width="360" height="360" alt="Linux" /></a>
</p>

<details>
  <summary><h3>File Management</h3></summary>

## File Management

1. <b>ls:</b> List directory contents.

```bash
ls
```

2. <b>cd</b>: Change directory.

```bash
cd [directory_path]
```

3. <b>pwd:</b> Print working directory.

```bash
pwd
```

4. <b>cp</b>: Copy files or directories.

```bash
cp [source] [destination]
```

5. <b>mv</b>: Move/rename files or directories.

```bash
mv [source] [destination]
```

6. <b>rm</b>: Remove/delete files or directories.

```bash
rm [file_or_directory]
```

7. <b>mkdir</b>: Create a directory.

```bash
mkdir [directory_name]
```

8. <b>rmdir</b>: Remove an empty directory.

```bash
rmdir [directory_name]
```

9. <b>touch</b>: Create an empty file or update file timestamp.

```bash
touch [file_name]
```

10. <b>cat</b>: Concatenate and display the content of files.

```bash
cat [file_name]
```

11. <b>nano</b>: A simple text editor.

```bash
nano [file_name]
```

12. <b>vim</b>: A powerful text editor.

```bash
vim [file_name]
```

13. <b>man</b>: Display the manual pages for commands.

```bash
man [command]
```

16. <b>chmod</b>: Change file permissions.

```bash
chmod [permissions] [file]
```

17. <b>chown</b>: Change file owner and group.

```bash
chown [owner:group] [file]
```

18. <b>find</b>: Search for files and directories.

```bash
find [directory] -name [filename_pattern]
```

19. <b>grep</b>: Search for patterns in files.

```bash
grep [pattern] [file]
```

20. <b>tar</b>: Create or extract compressed archive files.

```bash
tar -cvf [archive_name.tar] [files/directories]
tar -xvf [archive_name.tar]
```

21. <b>gzip</b>: Compress or decompress files.

```bash
gzip [file]
```

22. <b>gunzip</b>: Decompress files.

```bash
gunzip [file.gz]
```

23. <b>awk:</b> A versatile pattern scanning and processing language.

```bash
awk [options] 'pattern {action}' [file]
```

24. <b>sed:</b> Stream editor for filtering and transforming text.

```bash
sed [options] 's/pattern/replacement/' [file]
```

25. <b>zip:</b> Create a compressed archive.

```bash
zip [options] archive_name.zip [files/directories]
```

26. <b>unzip:</b> Extract files from a compressed archive.

```bash
unzip [options] archive_name.zip
```

27. <b>du:</b> Display file and directory space usage.

```bash
du [options] [directory]
```

28. <b>df:</b> Display disk space usage.

```bash
df [options]
```

29. <b>file:</b> Determine file type.

```bash
file [options] file_name
```

30. <b>ln:</b> Create hard or symbolic links.

```bash
ln [options] source [link_name]
```

31. <b>basename:</b> Strip directory and suffix from filenames.

```bash
basename [options] file_name
```

32. <b>dirname:</b> Strip last component from filenames.

```bash
dirname [options] file_name
```

<p>These commands cover various miscellaneous utilities in Linux. Always consult the respective man pages for detailed information and options for each command (man <command>).</p>

</details>

<details>
  <summary><h3>System Information</h3></summary>
  
  ## System Information

1. <b>uname</b>: Display system information.

```bash
uname [options]
```

2. <b>hostname:</b> Show or set the system's host name.

```bash
hostname [options]
```

3. <b>lsb_release:</b> Display distribution-specific information.

```bash
lsb_release [options]
```

4. <b>uptime:</b> Display system uptime.

```bash
uptime
```

5. <b>date:</b> Display or set the system date and time.

```bash
date [options]
```

6. <b>cal:</b> Display a calendar.

```bash
cal [options]
```

7. <b>whoami:</b> Display current username.

```bash
whoami
```

8. <b>w:</b> Show who is logged on and what they are doing.

```bash
w [options]
```

9. <b>finger:</b> Display user information.

```bash
finger [username]
```

10. <b>ps:</b> Display information about running processes.

```bash
ps [options]
```

11. <b>top:</b> Display system processes in real-time.

```bash
top
```

12. <b>htop:</b> Interactive process viewer.

```bash
htop
```

13. <b>free:</b> Display amount of free and used memory in the system.

```bash
free [options]
```

14. <b>vmstat:</b> Display virtual memory statistics.

```bash
vmstat [options]
```

15. <b>lscpu:</b> Display information about the CPU architecture.

```bash
lscpu
```

16. <b>lsblk:</b> Display block device information.

```bash
lsblk [options]
```

17. <b>df:</b> Display disk space usage.

```bash
df [options]
```

18. <b>du:</b> Display file and directory space usage.

```bash
du [options]
```

19. <b>ifconfig:</b> Display network interface information (deprecated, use ip).

```bash
ifconfig [interface]
```

20. <b>ip:</b> Display and manipulate routing, devices, policy routing, and
    tunnels.

```bash
ip [options] [object] [command]
```

21. <b>route:</b> Show or manipulate the IP routing table.

```bash
route [options]
```

22. <b>ss:</b> Display socket statistics.

```bash
ss [options]
```

23. <b>lsof:</b> List open files.

```bash
lsof [options]
```

24. <b>netstat:</b> Display network statistics.

```bash
netstat [options]
```

25. <b>iwconfig:</b> Configure wireless network interfaces.

```bash
iwconfig [options]
```

26. <b>uname -a:</b> Display all available system information.

```bash
uname -a
```

27. <b>cat /proc/cpuinfo:</b> Display detailed CPU information.

```bash
cat /proc/cpuinfo
```

28. <b>cat /proc/meminfo:</b> Display detailed memory information.

```bash
cat /proc/meminfo
```

29. <b>ls /proc:</b> Explore various system information available in the /proc
    directory.

```bash
ls /proc
```

30. <b>dmesg:</b> Display or control the kernel ring buffer.

```bash
dmesg [options]
```

<p>These commands cover various miscellaneous utilities in Linux. Always consult the respective man pages for detailed information and options for each command (man <command>)</p>.
</details>
