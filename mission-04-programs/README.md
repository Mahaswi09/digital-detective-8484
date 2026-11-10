# Mission 4: How Programs Run

## 1. Task / objective

To run a simple Python program and compare how compilers and interpreters translate or execute programs.

## 2. Work completed

I created `hello.py`, ran it with Python 3 from the Terminal, and completed a table comparing a compiler and an interpreter.

### Task 4.1: Create and Run a Python Program

- Program in `hello.py`: `print("Hello from Python")`
- Command used: `python3 mission-04-programs/hello.py`
- Output message: `Hello from Python`
- What I understood: When I ran the command, Python followed the instructions in my code. It did not create a new file, it just showed the result in the Terminal. This shows that Python is an interpreter, because it reads and runs my code and shows the result directly.

### Task 4.2: Compare Compiler and Interpreter

| Point | Compiler | Interpreter |
|---|---|---|
| When translation / execution happens | Translates the whole code before running it. | Reads and runs the code while executing it. |
| Typical output | Creates a separate runnable file. | Shows the result directly in the Terminal. |
| One example | C using `gcc`. | Python. |
| One advantage | Makes the program run faster. | Makes testing and finding mistakes easier. |

**Difference between a compiler and an interpreter**

As the table shows, a compiler translates the whole program before running it, while an interpreter reads and runs the code while the program is running. A compiler usually creates a separate runnable file, while an interpreter shows the result directly. A compiler helps programs run faster, but an interpreter makes testing easier, as I saw when `hello.py` ran straight away.

## 3. Commands / tools used

- `python3` – Runs a Python file using the Python interpreter.
- `print()` – A Python function that displays a message on the screen.
- `git status` – Shows which files have changed.
- `git add` – Selects files to save.
- `git commit` – Saves changes with a message.
- `git push` – Uploads commits to GitHub.
- VS Code – Used to write `hello.py` and this README.

## 4. My understanding

I understood the difference between a compiler and an interpreter. A compiler translates the whole program before it runs, and an interpreter reads and runs the code while it executes. Python is an interpreter, because it read my code and showed the result directly in the Terminal without creating a separate file.

## 5. Difficulties faced

I misspelled a folder name while typing the command in the Terminal, so Python could not find the file. I also had some trouble with formatting in my README.

## 6. How I resolved them

I read the error message, noticed the typo in the folder name, and typed the command again correctly. I fixed the formatting by adding blank lines and removing extra code lines.

## 7. Evidence / files

- `mission-04-programs/hello.py`
- `mission-04-programs/README.md`

## 8. Commit details

- Commit message: `Compare compilers and interpreters`
- A later commit, `Fix mistake in mission 4 README`, corrected a mistake in this README.
- Status: Pushed to GitHub.