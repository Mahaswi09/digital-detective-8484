# Mission 2 - Become comfortable with the terminal

## Task 2.1 - Explore basic terminal operations

| Operation / command name | What it does | What I observed |
|---|---|---|
| Current-directory display: `pwd` | Displays the complete path of the current working directory. | It showed the complete path of my current directory. |
| Directory listing: `ls` | Lists all the files and directories. | It showed my README.md, the evidence folder and all the mission folders. |
| Detailed listing: `ls -l` | Lists all the files and directories along with their permissions. | It displayed detailed information such as file permissions, ownership, file sizes and modification dates. |
| Change directory: `cd` | Changes the current working directory. | It took me to the specified folder. |
| Create directory: `mkdir` | Creates a new directory. | It created a new folder in my current working directory. |
| Create empty file: `touch` | Creates a new file. | It created a new file in my current working directory. |
| Copy file: `cp` | Copies files. | It created a duplicate of the copied file. |
| Move / rename file: `mv` | Moves a file to another location, and can also rename it. | It moved the file or renamed it. |
| Display file contents: `cat` | Shows the content in the file. | It displayed the text stored inside my file. |

## Task 2.2 - Practise file changes safely
1. What is the difference between replacing a file's contents and adding text to the end?
   The existing content of the file is erased and is replaced with new content. And for this ">" is used. Adding text to file is adding new content to the file without erasing the prevoius content. For this ">>" is used. 
2. What is the difference between copying a file and moving a file?
   Copying creates a duplicate of the copied file and the original file remains unchanged in the original location. Whereas, in moving, the file is completely moved from one directory location to the other and file is removed from the original directory. 
3. What information does the current-directory display provide?
   It provides the complete path of the directory where I'm currently working in. 
4. Why is a directory-listing operation useful?
   It helps users identify available files, navigate directories, and manage their data efficiently.

## Task 2.3 - Understand flags and pipes
| Command | What it showed |
|---|---|
| `ls` | It displayed only the names of files and directories in the current location. |
| `ls -l` | It displayed additional details such as file permissions, ownership, file size, and modification date. |
| `ls -lah` | It displayed hidden files and directories, including `.` and `..`, along with detailed information. It also showed file sizes in a human-readable format, such as `34B` instead of `34`

## Task 2.4 - Understand package managers
1. What I found?
   Homebrew installed of version 7.0.9. I checked the version using the brew --version. Few of the packages include, git, ffmpeg, json-c
2. Why package mangers are useful?
   Package managers make it easier to install, update, and manage software on a computer. They automatically handle dependencies and help keep applications up to date, saving time and reducing manual effort. If Homebrew is not installed, It automatically handles dependencies, checks for available updates, and simplifies software management without requiring users to install everything manually.

