### What are the main area of concern when monitoring a system? (EX: CPU load, disk usage, ...)

When monitoring a system, there are several key areas of concern that administrators typically focus on like:

- CPU Usage
- Memory Usage
- Disk Usage
- Network Traffic and Performance
- System Uptime and Availability
- Security and Log Files
- Backup and Recovery


### How can you check what are the most memory intensive running processes ?

Run command `htop` and press `SHIFT` + `M`  in your terminal  to sort processes by resident memory usage 

### What are log files? Where can you fin them on a typical Linux system ?

Log files are files that record system events, messages, and diagnostics information about different software, services, and the kernel itself. 

They are usually located in the `/var/log` directory.

### How can you check who where the last connected users, what they did, when they left ?

The `last` command is used to display a list of the last logged-in users. 

The `history` command while not a system-wide command, history can be used when logged in as the user or switched to the user's profile to see the command history

### What are the different metrics of health and performance of a system ?

- CPU Usage
- Memory Usage
- Disk Usage

### How can you check the uptime of a machine ?

By using the `uptime` command.

Example of output :

```bazaar
 14:32:01 up  2 days,  6:02,  1 user,  load average: 0.00, 0.01, 0.05
```

### How can you assess the network traffic ?

- `netstat`
Description: Displays active connections, routing tables, interface statistics, masquerade connections, and multicast memberships.
- `tcpdump`
Description: A powerful command-line packet analyzer; allows the user to display TCP/IP and other packets being transmitted or received over a network to which the computer is attached.
- `iftop`
Description: A console application that visualizes network traffic and bandwidth usage in real time.
- `iptraf`
A network traffic monitor that uses data collected by the kernel to provide a summary of network traffic.
- `bmon`
A tool that displays and logs bandwidth data and information.
- `Wireshark (GUI)`
A network protocol analyzer that lets you capture and interactively browse the traffic running on a computer network.