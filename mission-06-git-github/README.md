# Mission 6: Git and GitHub

## 1. Task / objective

To understand version control, stage and commit changes, create a branch, open and merge a Pull Request, and explain the Git collaboration workflow.

## 2. Work completed

I checked my repository status and history, practised staging and committing, created the `update-about` branch, added a "My Learning" section to the root README, opened and merged a Pull Request on GitHub, pulled the merged changes to my computer, and wrote a Git command glossary.

### Task 6.1: Understand the Basic Git Workflow

| Git operation | What it does in my own words |
|---|---|
| Check repository status | Shows which files have been changed. |
| Stage selected changes | Selects the files I want to save in a commit. |
| Create a commit | Saves a snapshot of my changes. |
| View commit history | Shows all the commits I made earlier. |

**Difference between staging and committing**

Staging (`git add`) means choosing which changes will go into the next save. Nothing is saved to history yet. Committing (`git commit`) saves everything I staged as one snapshot in the project history, with a message describing it.

### Task 6.2: Create and Use a Branch

- **Branch name:** `update-about`
- **Commands I used:**
  - `git switch -c update-about`
  - `git branch`
  - `git status`
  - `git add README.md`
  - `git commit -m "..."`
  - `git push -u origin update-about`
- **What I changed:** I added a "My Learning" section to the root README file.
- **Why `-u` was needed:** the new branch was not linked to GitHub yet, so `-u` linked it on the first push.

### Task 6.3: Create a Pull Request

- **PR title:** Add My Learning section to README
- **PR description:** I added a "My Learning" section to the root README that lists what I have learned so far.
- **Status:** Merged. My instructor asked me to merge it.
- **After merging:** I ran `git switch main` and `git pull` to bring the merged changes onto my computer.

**What is a branch?**

A branch is a separate place where I can make changes without disturbing the main project.

**What is a Pull Request?**

A Pull Request is a request to add my changes to the main project after someone checks them.

**Why are branches and Pull Requests useful?**

They help people work on different parts of the same project without disturbing each other's work. They also allow everyone to check the changes before adding them to the main project.

### Task 6.4: Build Your Git Command Glossary

| Git operation | Command | One-line explanation (my words) |
|---|---|---|
| Initialise a repository | `git init` | Starts Git in a folder to track changes. |
| Check status | `git status` | Shows which files have been changed. |
| Stage changes | `git add` | Selects the changes I want to commit. |
| Commit changes | `git commit -m` | Saves the selected changes with a message. |
| View history | `git log --oneline` | Shows the list of previous commits. |
| Create or list branches | `git branch` / `git switch -c` | Shows existing branches or creates a new branch. |
| Switch branches | `git switch` | Moves me from one branch to another. |
| Publish changes | `git push` | Uploads my commits to GitHub. |
| Retrieve remote changes | `git pull` | Gets the latest changes from GitHub to my computer. |

## 3. Commands / tools used

- `git status` – Shows which files have changed and what is staged.
- `git log --oneline` – Shows my recent commits, one short line each.
- `git add` – Stages the files I want in the next commit.
- `git commit` – Saves the staged changes with a message.
- `git switch -c` – Creates a new branch and moves onto it.
- `git branch` – Lists branches and shows which one I am on.
- `git push -u origin update-about` – Publishes the new branch to GitHub.
- `git switch main` – Moves back to the main branch.
- `git pull` – Brings the latest changes from GitHub to my computer.
- GitHub (browser) – Used to create, review and merge the Pull Request.
- VS Code – Used to write and edit the README files.

## 4. My understanding

I learned how Git helps me save and track changes in my project. I understood that staging selects the files and committing saves those changes. I also learned how to create branches and switch between them, and how a Pull Request lets my changes be reviewed and merged into the main branch.

## 5. Difficulties faced

Initially, I found it difficult to remember which branch I was working on and when to switch branches. I was also confused about the difference between staging, committing and pushing changes.

## 6. How I resolved them

I used `git branch` and `git status` to check my current branch before making changes. I practised the add, commit and push steps until I could tell them apart.

## 7. Evidence / files

- `mission-06-git-github/README.md`
- The `update-about` branch and the merged Pull Request, visible on GitHub
- The "My Learning" section in the root `README.md`

## 8. Commit details

- Commit messages: `Add git workflow notes for mission 6`, `Add My Learning section to README.md` (on the `update-about` branch), and `Complete Git and GitHub collaboration mission`
- Pull Request: merged into `main`
- Status: Pushed to GitHub.