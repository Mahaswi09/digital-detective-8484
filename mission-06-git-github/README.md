# Mission 6 - Git and GitHub

## Task 6.1 - Understand the basic Git workflow

| Git operation | What it does in my own words |
|---|---|
| Check repository status | Shows which files have been changed. |
| Stage selected changes | Selects the files I want to save in a commit. |
| Create a commit | Saves a snapshot of my changes. |
| View commit history | Shows all the commits I made earlier. |

### Difference between staging and commit
Staging (git add) means choosing which changes will go into the next save. Nothing is saved to history yet. You’re just putting files in a “ready” area.
Committing (git commit) means saving everything in that ready area as one snapshot in the project history, with a message describing it.

## Task 6.2 - Create and use a branch

- **Branch name:** `update-about`

- **Commands I used:**
  - `git switch -c update-about`
  - `git branch`
  - `git status`
  - `git add README.md`
  - `git commit -m "..."`
  - `git push -u origin update-about`

- **What I changed:** I added a "My Learning" section to the main README file.

## Task 6.3 - Create a Pull Request

- **PR Title:** 
- **PR Description:** 
- **Status:** Open, waiting for my instructor to say whether to merge.

### What is a Branch?

A branch is a separate place where I can make changes without disturbing the main project.

### What is a Pull Request?

A Pull Request is a request to add my changes to the main project after someone checks them.

### Why are Branches and Pull Requests Useful?

They help people work on different parts of the same project without disturbing each other's work. They also allow everyone to check the changes before adding them to the main project.

## Task 6.4 - Build your Git command glossary

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

## What I Understood

I learned how Git helps me save and track changes in my project. I understood that staging selects the files and committing saves those changes. I also learned how to create branches and switch between them. 

## Difficulty Faced

Initially, I found it difficult to remember which branch I was working on and when to switch branches. I was also confused about the difference between staging, committing and pushing changes.





