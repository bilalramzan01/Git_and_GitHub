# Git Undo & Log Notes

This file covers **undoing changes** and **viewing commit history** in Git. Perfect for quick reference.

---

## 1. Undo Staged Changes

Used when **changes are added (staged) but not yet committed**.

- **git reset <filename>** → Unstages a specific file, keeping its changes in your working directory.  
- **git reset** → Unstages all staged files, keeping changes in your working directory.  

**Modern Alternative:**

- **git restore --staged <filename>** → Unstages a file. Safer and more explicit than `git reset`.

---

## 2. Undo Last Commit

Used when **changes are already committed** but you want to undo them.

- **git reset HEAD~1** → Undo the last commit **but keeps changes** in working directory. *(Soft/Mixed reset: safe undo, can edit and recommit)*  
- **git reset --hard HEAD~1** → Undo the last commit **and deletes all changes** made in that commit. *(Hard reset: permanent, use with caution)*  

**Tip:** Both move the **tip of your branch back by one commit**. Use soft/mixed to save work, hard to wipe everything completely.

---

## 3. Undo Committed Changes (Jump to Specific Commit)

Used when you want to **go back to a specific commit** in Git history.

- **git reset <commit-id>** → Move branch to specific commit, keeping changes from later commits as **unstaged**.  
- **git reset --hard <commit-id>** → Move branch to specific commit and **delete all changes after it permanently**.

**How it works:**  
- `<commit-id>` = SHA-1 hash of the commit.  
- Git restores your project to the **exact snapshot** of that commit.  
- Soft reset = save work; hard reset = fully wipe unwanted commits.

---

## 4. Git Log --oneline

The `git log --oneline` command shows a **condensed view of your commit history**.

- Each line = **one commit**  
- Format: **Commit ID + Commit Message**

**Example Output:**

| Commit ID | Branch/Pointer Info | Commit Message |
|-----------|-------------------|----------------|
| 7d5493e | (HEAD -> main) | new line added |
| 2db8f08 | — | Changes by Tariq Mahoom |
| 2df18a3 | (origin/function1) | Changes made in html |
| b0ba3ec | — | Readme file created |
| 8db439a | — | CSS File Created |
| 3d0ad17 | — | New HTML file created |

**Key Notes:**  
- **Commit ID:** Unique 7-character hash identifying the commit.  
- **Branch/Pointer Info:** Shows current branch (`HEAD`) and remote tracking info.  
- **Commit Message:** Short description of the changes.

✅ Tip: Use `git log --oneline` for a **quick overview of your project history**.