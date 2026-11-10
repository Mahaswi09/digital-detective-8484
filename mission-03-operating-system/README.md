# Mission 3: Understand the Operating System

## 1. Task / objective

To explore my operating system, observe running processes and storage, understand paths and file permissions, and describe the responsibilities of an operating system.

## 2. Work completed

I checked my system details, account, storage and activity, learned what processes and PIDs are, compared absolute and relative paths, read the permission letters of a file, and explained six operating-system responsibilities.

### Task 3.1: Explore the Operating System

| Information explored | What it tells you | My observation (privacy-safe) |
|---|---|---|
| Operating system / system details | It tells me the operating system, its version, and basic system information. | My Mac runs macOS version 26.6.2. |
| Current account identity | It tells me the username of the currently logged-in user. | It printed my username, [redacted]. |
| Available and used storage | It tells me the total disk space, the amount of storage used, and the available free space. | The disk is about 926 GB, 66 GB is used and 839 GB is free. |
| System activity snapshot | It tells me the current system activity, including running processes and CPU usage. | There were 677 processes, the CPU was about 87% idle, and the remaining 13% was being used by programs and the system. |

### Task 3.2: Understand Processes

**1. What is a process?**

A process is a program that is currently running on a computer. It uses system resources such as CPU and memory to perform its tasks.

**2. What does the PID column represent?**

PID stands for Process ID. It is a unique identification number assigned to each running process, which helps the operating system identify and manage it.

**3. Two examples of processes on my computer**

- Google Chrome: a process that runs the web browser and helps access websites.
- Terminal: a process that allows me to execute commands and interact with the operating system.

### Task 3.3: Understand Paths and Permissions

**Paths**

**1. How did the displayed location change when I moved into the subfolder and back?**

When I moved into a subfolder using the `cd` command, the displayed path changed to show the new directory location. When I moved back to the parent directory, the path returned to its previous location.

**2. Difference between an absolute and a relative path**

- Absolute path: specifies the complete location of a file or directory, starting from the root directory.
- Relative path: specifies the location of a file or directory in relation to the current working directory.

**3. One absolute example and one relative example**

- Absolute: `/Users/[redacted]/Desktop/digital-detective-8484/mission-03-operating-system/README.md`
- Relative: `mission-03-operating-system/README.md`

**Permissions**

**1. The letters**

The owner's permissions for `notes.txt` are `rw-`, which means the owner can read and write the file but cannot execute it.

**2. What that means**

- Read: yes, because the first letter is `r`.
- Write: yes, because the second letter is `w`.
- Execute: no, because the third character is a dash (`-`).

**3. What r, w and x mean**

| Permission | Meaning | My example |
|---|---|---|
| r (read) | I can look at the contents of a file. | I used `cat notes.txt` to read the contents of the file. |
| w (write) | I can change the contents of a file. | I used `echo "This is line two" >> notes.txt` to add a new line to the file. |
| x (execute) | I can run a file as a program or access a directory. | I used `cd` to enter folders, which requires execute (`x`) permission on the directory. |

### Task 3.4: Operating System Responsibilities

| OS responsibility | My explanation | Example |
|---|---|---|
| Process management | The OS manages all running programs and decides how much CPU time each program gets. | I saw 677 running processes when I used the `top` command. |
| Memory management | The OS manages RAM and distributes memory to different programs whenever needed. | I saw the memory usage displayed under `PhysMem` in the `top` command. |
| Device management | The OS helps the computer communicate with and control its hardware devices. | macOS manages devices such as the keyboard, mouse, and display. |
| File management | The OS helps me create, find, copy, move, and organize files and folders. | I used `ls`, `cp`, `mv`, and `>>` while working with files. |
| User interface / shell | The shell allows me to interact with the operating system by entering commands. | I used Terminal to execute commands such as `pwd`, `ls`, and `cd`. |
| Security and permissions | The OS controls who can read, write, or execute files and directories. | I observed that `notes.txt` had `rw-` permissions, meaning the owner could read and write but not execute it. |

## 3. Commands / tools used

- `sw_vers` – Shows the macOS name and version.
- `whoami` – Shows the account I am logged in as (kept private as [redacted]).
- `df -h` – Shows total, used and free disk space in readable sizes.
- `top -l 1 | head -12` – Takes one snapshot of system activity and keeps the first 12 lines.
- `ps -ax -o pid,comm | head -15` – Lists running processes with their PID and name.
- `pwd` – Displays the current folder location.
- `cd` – Moves between folders.
- `ls -l` – Shows detailed file information, including permission letters.
- `|` – Sends the output of one command into another.
- `git status`, `git add`, `git commit`, `git push` – Used to check, stage, save and upload my work.
- VS Code – Used to write and edit the README file.

## 4. My understanding

I understood that an operating system manages the computer's hardware, memory and files. A process is a running program, and each one has its own PID so the OS can manage it. With `df -h` I saw that most of my disk is still free, and with `top` I saw that the CPU was mostly idle. I also learned the difference between absolute and relative paths, and that `r`, `w` and `x` control whether a file can be read, changed or run.

## 5. Difficulties faced

Initially, I found it difficult to understand the permission letters. I also had trouble when my table did not show properly in the preview.

## 6. How I resolved them

I practised reading the `ls -l` output until I could split the letters into owner, group and others. I fixed the table by removing the extra code lines around it.

## 7. Evidence / files

The Mission 3 folder contains my README file with the system observations, process answers, path and permission notes, and the OS responsibilities table. No private details are included.

## 8. Commit details

- Commit message: `Document operating system and file management`
- Status: Pushed to GitHub.