# **Report Vietnix Linux Basic**
![](https://3.imimg.com/data3/BG/BV/MY-15454259/linux-operating-system.png)

#           PART 01: 
1. <a href='#1'> Check Diskpace
1. <a href='#2'> Check Partitions
1. <a href='#3'> Check cpu, ram, network
1. <a href='#4'> Process Monitor
1. <a href='#5'> List files/ directories
1. <a href='#6'> Find, copy, move,... files/directories
1. <a href='#7'> Basic and advanced decentralization
1. <a href='#8'> Editors command
1. <a href='#9'> Mount/ Unmount
1. <a href='#10'> Symbolic Links
1. <a href='#11'> Hard Links
1. <a href='#12'> Compressed/ Depressed
1. <a href='#13'> Bandwidth monitoring
1. <a href='#14'> nmap, telnet, ping, ssh, transfer files from local to public host
1. <a href='#15'> Generate ssh-key
1. <a href='#16'> Read file contents without editor
1. <a href='#17'> Add content to the end of the file
1. <a href='#18'> Basic command Linux
1. <a href='#19'> Standard Input, Output, Error
1. <a href='#20'> Redirecting Standard Input, Output, Error
1. <a href='#21'> /dev/null

***
## *man* 
Command in Linux is used to display the user manual of any command that we can run on the terminal.
* Syntax: 
```
man [COMMAND NAME]
```

<div id='1'></div>

### 1. CheckDiskpace
- Shows the amount of disk space used and available on Linux file systems.
* Syntax: 
``` 
df -a 
```
  
![](src/01_df.png)

<div id='2'></div>

### 2. Check Partitions
- The lsblk command lists all the block devices of your system along with their logical partitions. 
* Syntax: 
``` 
lsblk 
```

![](src/02_lsblk.png)

- The fdisk command that stands for Format-disk or Fixed-disk is basically used to create or delete hard disk partitions.
* Syntax: 
```
fdisk -l
```

![](src/02_fdisk.png)

<div id='3'></div>

### 3. Check cpu, ram, network
#### 3.1 CPU
- **lscpu** is a small and quick command that does not need any options.
* Syntax: 
```
lscpu
```
![](src/03_cpu.png)

#### 3.2 RAM 

- The most popular command in order to check your RAM on Linux is to use the **free** command.
* Syntax: 
```
free -h
```

![](src/03_ram.png)

#### 3.3 Network

- **netstat** is a command line tool for monitoring incoming and outgoing network packets statistics as well as interface statistics. 
* Syntax: 
```
netstat
```

![](src/03_netstat.png)

```
netstat -lnp 
    * -lnp: Listen all active listening ports connection
```

![](src/03_netstat2.png)

<div id='4'></div>

### 4. Process Monitor

- The **top** command used to dipslay all the running and active real-time processes in ordered list and updates it regularly.
* Syntax: 
```
top
```

![](src/04_top.png)

-  **Htop** is a much advanced interactive and real time Linux process monitoring tool.
* Syntax:
```
htop
```

![](src/04_htop.png)

- **ps** command will report a snapshot of the current processes.
* Syntax:

```
ps -aux
    * -aux: Print all process on the server
```

![](src/04_ps.png)

<div id='5'></div>

### 5. List files/ directories
- The **ls** command also accepts some flags which are additional information that changes how files or directories are listed in your terminal.
* Syntax: 
```
ls -la
    -la: to list files or directories in a table format with extra information including hidden files or directories
```

[](src/05_ls.png)

<div id='6'></div>