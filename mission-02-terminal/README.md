# Mission 2: Become Comfortable with the Terminal

## 1. Task / objective

To learn basic Terminal commands, practise creating and managing files and directories, understand command flags and pipes, and explore package managers.

## 2. Work completed

I practised basic Terminal operations, learned how to make file changes safely, explored command flags and pipes, and checked Homebrew and its installed packages.

### Task 2.1: Basic Terminal Operations

| Operation / command name | What it does | What I observed |
|---|---|---|
| Current-directory display: `pwd` | Displays the complete path of the current working directory. | It showed the complete path of my current directory. |
| Directory listing: `ls` | Lists files and directories. | It showed my README.md, the evidence folder and all the mission folders. |
| Detailed listing: `ls -l` | Lists files and directories along with their permissions and other details. | It displayed file permissions, ownership, file sizes and modification dates. |
| Change directory: `cd` | Changes the current working directory. | The prompt changed to show the folder I entered. |
| Create directory: `mkdir` | Creates a new directory. | It created a new folder in my current working directory. |
| Create empty file: `touch` | Creates a new empty file. | It created a new file in my current working directory. |
| Copy file: `cp` | Copies files from one location to another. | It created a duplicate while keeping the original file. |
| Move / rename file: `mv` | Moves a file to another location or renames it. | It changed `notes-backup.txt` to `notes-copy.txt`. |
| Display file contents: `cat` | Displays the contents of a file. | It displayed the two lines stored inside `notes.txt`. |

### Task 2.2: Practise File Changes Safely

I created a folder, added two lines to a file, checked its contents and made a backup copy before renaming it.

**Commands used:**

```bash
mkdir terminal-practice
cd terminal-practice
echo "This is line one" > notes.txt
echo "This is line two" >> notes.txt
cat notes.txt
cp notes.txt notes-backup.txt
mv notes-backup.txt notes-copy.txt
```

**1. What is the difference between replacing a file's contents and adding text to the end?**

Replacing removes the existing content and puts new content in its place using `>`. Adding text using `>>` puts new content at the end without removing the previous content.

**2. What is the difference between copying a file and moving a file?**

Copying creates a duplicate of the file while keeping the original in its location. Moving transfers the file to another location and removes it from the original location.

**3. What information does the current-directory display provide?**

It provides the complete path of the directory where I am currently working.

**4. Why is a directory-listing operation useful?**

It helps users identify available files, navigate directories and manage their data efficiently.

### Task 2.3: Understand Flags and Pipes

| Command | What it showed |
|---|---|
| `ls` | It displayed only the names of files and directories in the current location. |
| `ls -l` | It displayed additional details such as file permissions, ownership, file size and modification date. |
| `ls -lah` | It displayed hidden files and directories, including `.` and `..`, along with detailed information and human-readable file sizes. |

**What is a pipe?**

A pipe (`|`) sends the output of one command as the input to another command.

**Command used:** `ls -lah | head -3`

- Left side (`ls -lah`): displays files and directories with detailed information, including hidden files.
- Right side (`head -3`): displays only the first three lines of the output.
- Observation: it showed only the first three lines of the detailed listing.

### Task 2.4: Understand Package Managers

**1. What did I find?**

Homebrew version 7.0.9 was installed on my Mac. I checked the version using `brew --version`. Some installed packages included Git, FFmpeg and JSON-C. The `brew list` command showed approximately 24 packages. I did not install or uninstall anything.

**2. Why are package managers useful?**

Package managers make it easier to install, update and manage software on a computer. They automatically handle dependencies and help keep applications up to date, saving time and reducing manual effort.

## 3. Commands / tools used

- `pwd` – Displays the current directory path.
- `ls` – Lists files and directories.
- `ls -l` – Displays detailed file and directory information.
- `cd` – Changes the current directory.
- `mkdir` – Creates a new directory.
- `touch` – Creates an empty file.
- `cp` – Copies files.
- `mv` – Moves or renames files.
- `cat` – Displays file contents.
- `echo` – Writes text into a file.
- `>` – Replaces existing file contents.
- `>>` – Adds text to the end of a file.
- `ls -lah` – Displays hidden files and detailed information in a readable format.
- `|` – Sends the output of one command to another command.
- `head -3` – Displays the first three lines of output.
- `brew --version` – Checks the installed Homebrew version.
- `brew list` – Lists installed Homebrew packages.
- `git status` – Shows the current changes in the repository.
- `git add` – Selects files to save.
- `git commit` – Saves changes with a message.
- `git push` – Uploads commits to GitHub.
- VS Code – Used to write and edit the README file.

## 4. My understanding

I learned how to use Terminal commands to navigate directories, create, copy, move and view files. I also understood the difference between `>` and `>>`, learned how flags provide additional information, how pipes connect commands, and how package managers help install and manage software.

## 5. Difficulties faced

Initially, I found it difficult to remember the different Terminal commands and sometimes started working from the wrong directory.

## 6. How I resolved them

I used `pwd` to check my current location and practised the commands to understand their purpose and output.

## 7. Evidence / files

The Mission 2 folder contains my README file and the `terminal-practice` folder with `notes.txt` and `notes-copy.txt`.

## 8. Commit details

- Commit message: `Complete Terminal and file management mission`
- Status: Pushed to GitHub.
