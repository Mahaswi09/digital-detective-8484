# Mission 3 - Understanding the Operating system

## Task 3.1 - Explore the operating system

| Information explored | What it tells you | My observation (privacy-safe) |
|---|---|---|
| Operating system / system details | It tells me the operating system, its version, and basic system information. | My Mac runs macOS version 26.6.2. |
| Current account identity | It tells me the username of the currently logged-in user. | It printed my username, [redacted]. |
| Available and used storage | It tells me the total disk space, the amount of storage used, and the available free space. | The disk is about 926 GB, 66 GB is used and 839 GB is free. |
| System activity snapshot | It tells me the current system activity, including running processes and CPU usage. | There were 677 processes, the CPU was about 87% idle, and the remaining 13% was being used by programs and the system. |

## Task 3.2 - Understand processes
1. What is a process?
A process is a program that is currently running on a computer. It uses system resources such as CPU and memory to perform its tasks.
2. What does the PID column represent?
PID stands for Process ID. It is a unique identification number assigned to each running process, which helps the operating system identify and manage it
3. Two examples of processes on my computer
 Google Chrome: A process that runs the web browser and helps access websites.
 Terminal: A process that allows me to execute commands and interact with the operating system.

## Task 3.3 - Understand paths and permissions
## Paths
1. How the displayed location changed when you moved into the subfolder and back?
When I moved into a subfolder using the cd command, the displayed path changed to show the new directory location. When I moved back to the parent directory, the path returned to its previous location.
2. Difference between an absolute and a relative path
Absolute path: Specifies the complete location of a file or directory, starting from the root directory.
Relative path: Specifies the location of a file or directory in relation to the current working directory.
3. One absolute example (with [redacted]) and one relative example.
Absolute, /Users/[redacted]/Desktop/digital-detective-8484/mission-03-operating-system/README.md
Relative, mission-03-operating-system/README.md

## Permissions
1. The letters
The owner's permissions for notes.txt are rw-, which means the owner has permission to read and write the file but does not have permission to execute it.
2. What that means?
- Read: yes, because the first letter is r.
- Write: yes, because the second letter is w.
- Execute: no, because the third character is a dash (-).
3. What r, w, x mean
Read (r)
- Meaning: I can look at the contents of a file.
- My example: I used cat notes.txt to read the contents of the file.
Write (w)
- Meaning: I can change the contents of a file.
- My example: I used echo "This is line two" >> notes.txt to add a new line to the file.
Execute (x)
- Meaning: I can run a file as a program or access a directory.
- My example: I used cd to enter folders, which requires execute (x) permission on the directory

## Task 3.4 - Explain operating-system responsibilities

| OS responsibility | My explanation | Example |
|---|---|---|
| Process management | The OS manages all running programs and decides how much CPU time each program gets. | I saw 677 running processes when I used the `top` command. |
| Memory management | The OS manages RAM and distributes memory to different programs whenever needed. | I saw the memory usage displayed under `PhysMem` in the `top` command. |
| Device management | The OS helps the computer communicate with and control its hardware devices. | macOS manages devices such as the keyboard, mouse, and display. |
| File management | The OS helps me create, find, copy, move, and organize files and folders. | I used `ls`, `cp`, `mv`, and `>>` while working with files. |
| User interface / shell | The shell allows me to interact with the operating system by entering commands. | I used Terminal to execute commands such as `pwd`, `ls`, and `cd`. |
| Security and permissions | The OS controls who can read, write, or execute files and directories. | I observed that `notes.txt` had `rw-` permissions, meaning the owner could read and write but not execute it. |

## What I understood?
I understood that an operating system manages the computer's hardware, memory, files. I learned the meaning of read(r), write(w), execute(x) permissions. 

## Difficulties faced
Initially, I found it difficult to undrerstand the permission commands. However, by practising the commands, I started understanding them better. 



