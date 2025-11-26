# 📂 Project 2.1-LINUX      
                        LAB 245  Managing Long Files

In this lab, I explored how Linux systems generate, store, and manage log files. The main goal was to understand where logs are located, how to read them, and how automated log rotation helps keep the system organized and efficient. I worked with tools like cat, less, tail, and journalctl to view different types of logs and monitor system activity. I also examined how logrotate controls the size, rotation schedule, and archival process of log files. This lab helped me understand the importance of logs for troubleshooting, performance monitoring, and maintaining the overall health of a Linux system.

✔ Project Objectives

Understand where system and application logs are stored and how to access them.

Use Linux commands to view and monitor log files efficiently.

Learn how log rotation works with logrotate to manage file size, retention, and archiving.

Understand the role of logs in troubleshooting, system performance tracking, and security auditing.

✔ What I Did

Explored the /var/log directory to see where different types of logs are stored.

Used cat, less, and tail to view log files and monitor system activity.

Practiced using journalctl to filter and analyze systemd-managed logs.

Reviewed logrotate configuration files to understand how logs are rotated, compressed, and archived.

Checked older rotated log files to see how long-term log storage works.

Observed how proper log management supports troubleshooting and overall system health.

Difficulties Encountered

Understanding log types and locations: At first, it was a bit confusing to know which logs were in /var/log and which were managed by journalctl.

Reading long log files: Some logs were very large, which made it tricky to find specific entries.

Interpreting log entries: Certain messages, especially errors, were technical and not immediately clear.

Understanding logrotate configuration: Figuring out how rotation schedules, retention policies, and compression worked required careful reading.

Permissions issues: Some logs needed elevated permissions to access, so I had to troubleshoot access errors.


<img width="1346" height="723" alt="Managing Log files " src="https://github.com/user-attachments/assets/6c933787-645f-4e54-9a84-f221ad528969" />



📂 Project 2.2

                               LAB 249 The bash shell 

In this lab, I explored the Bash shell, which is the command-line interface for interacting with a Linux system. The main goal was to understand how to use Bash commands, navigate the file system, manage files and directories, and execute scripts. This lab provided hands-on experience with essential Linux commands, shell features, and basic scripting, helping me become more comfortable working in a command-line environment.

✔ Project Objectives

Understand how to use the Bash shell to interact with Linux.

Navigate the file system using commands like cd, ls, and pwd.

Manage files and directories using commands such as cp, mv, rm, and mkdir.

Learn how to view, create, and edit files with commands like cat, nano, and touch.

Understand the basics of executing shell scripts and using command-line arguments.

Learn how to combine commands and use pipes and redirection to perform complex tasks.

✔ What I Did

Navigated directories using cd and listed contents with ls.

Viewed the current directory path using pwd.

Created, copied, moved, and deleted files and directories using touch, cp, mv, rm, and mkdir.

Viewed and edited file contents using cat and nano.

Practiced using input/output redirection (>, >>, <) and pipes (|) to combine commands.

Learned to execute simple Bash scripts and pass arguments to them.

Explored built-in Bash commands and shortcuts to improve efficiency while working in the shell.



<img width="1365" height="719" alt="249 Lab The bash shell" src="https://github.com/user-attachments/assets/f9c2f812-c77a-4965-8e20-b453bcc4329a" />


Difficulties Encountered

Remembering command syntax: Some commands had multiple options and flags that were easy to forget.
Understanding redirection and pipes: Combining commands using > or | was confusing at first.
File permissions: Running scripts sometimes failed due to lack of execute permissions, which required troubleshooting with chmod.
Navigating directories quickly: Managing paths and relative vs. absolute references was tricky initially.
Error messages: Mis-typed commands or wrong paths produced errors that needed careful reading to fix



