# Git Branching & Merging Notes

Branches let you work on different versions of a project **without affecting the main line**.

---

## Branch Commands

- **git branch** → Shows all local branches.  
- **git branch <new-branch>** → Creates a new branch.  
- **git branch -m <old-name> <new-name>** → Renames a branch.  
- **git checkout <branch-name>** → Switches to another branch.  
- **git checkout -b <branch-name>** → Creates and switches to a new branch in one step.  
- **git branch -d <branch-name>** → Deletes a branch (if already merged).  
- **git branch -D <branch-name>** → Force deletes a branch (even if not merged).  

---

## Comparing & Syncing

- **git diff <branch-name>** → Compare commits, files, or branches.  
- **git pull origin main** → Download latest changes from GitHub and merge to local project.  

---

## Merging Code

- **Method 01: git merge** → Combine changes from one branch into another locally.  
- **Method 02: Pull Request (PR)** → Merge code via GitHub website using a pull request.  

---

## Merge Conflicts

- Happens when Git **cannot automatically merge** changes.  
- Occurs if the **same lines in the same file** were changed differently in multiple branches.  