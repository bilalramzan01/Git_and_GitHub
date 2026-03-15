# Important Git Commands

This file contains 15 commonly used Git commands with their explanations. You can use this as a **quick reference guide** for your Git learning notes.

---

| Command | Purpose / Explanation |
|---------|----------------------|
| `git init` | Initialize a new Git repository in your project folder. |
| `git status` | Check the status of your repository (tracked/untracked files, changes). |
| `git add <file>` | Stage a specific file for commit. |
| `git add .` | Stage all files in the current directory for commit. |
| `git commit -m "message"` | Commit staged files with a descriptive message. |
| `git log` | View the commit history of the repository. |
| `git branch` | List all branches in the repository. |
| `git branch <branch-name>` | Create a new branch. |
| `git checkout <branch-name>` | Switch to a specific branch. |
| `git merge <branch-name>` | Merge a branch into the current branch. |
| `git remote add origin <url>` | Link your local repository to a remote GitHub repository. |
| `git push -u origin <branch>` | Push your commits to the remote repository. |
| `git pull` | Pull the latest changes from the remote repository to your local repo. |
| `git clone <url>` | Copy an existing remote repository to your local machine. |
| `git diff` | Show changes between commits, branches, or staged files. |

---

## ✅ Tips

- Always **commit small changes frequently**.  
- Use **descriptive commit messages** for clarity.  
- Practice **branching and merging** to understand teamwork workflows.  
- Use `git pull` before starting work to avoid conflicts.  

# 10 Important Terminal Commands

This file contains 10 commonly used **terminal commands** for navigating and managing files in Git Bash, Windows Command Prompt, or any CLI environment.

---

| Command | Purpose / Explanation |
|---------|----------------------|
| `cls` | Clear the terminal screen. |
| `cd <folder>` | Change directory to the specified folder. Example: `cd Documents` |
| `cd ..` | Go up one directory level. |
| `mkdir <folder>` | Create a new folder. Example: `mkdir MyProject` |
| `rmdir <folder>` | Remove/delete an empty folder. |
| `rm -r <folder>` | Remove a folder and its contents (use with caution). |
| `pwd` | Show the current directory path (present working directory). |
| `ls` | List all files and folders in the current directory (Linux/macOS/Git Bash). |
| `dir` | List all files and folders in the current directory (Windows CMD). |
| `echo <text>` | Display text or variables in the terminal. Example: `echo Hello World` |

---

## ✅ Tips

- `cd` and `ls` are the **most used commands** for navigation.  
- `mkdir` + `cd` is a common workflow to create and enter a new project folder.  
- Use `cls` or `clear` to **keep your terminal organized**.  
- Be careful with `rm -r` as it **permanently deletes files/folders**.  