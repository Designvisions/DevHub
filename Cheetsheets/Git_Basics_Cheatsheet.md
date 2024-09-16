# Git Basics Cheat Sheet

## 1. Initialize a New Git Repository
```bash
git init
```
Creates a new Git repository in your current directory.

---

## 2. Clone a Repository
```bash
git clone https://github.com/username/repo-name.git
```
Clones an existing Git repository from GitHub to your local machine.

---

## 3. Check Repository Status
```bash
git status
```
Displays the status of your working directory and staging area.

---

## 4. Add Files to Staging Area
```bash
git add .
```
Stages all changes in your current directory for the next commit.

---

## 5. Commit Changes
```bash
git commit -m "Your commit message"
```
Commits staged changes to the local repository with a descriptive message.

---

## 6. Push Changes to Remote Repository
```bash
git push origin main
```
Pushes local commits to the `main` branch on the remote repository.

---

## 7. Pull Latest Changes from Remote Repository
```bash
git pull origin main
```
Fetches and integrates changes from the `main` branch of the remote repository.

---

## 8. Create a New Branch
```bash
git checkout -b new-branch
```
Creates and switches to a new branch.

---

## 9. Switch Between Branches
```bash
git checkout branch-name
```
Switches to an existing branch.

---

## 10. Merge a Branch
```bash
git merge branch-name
```
Merges the specified branch into your current branch.

---

## 11. Delete a Branch
```bash
git branch -d branch-name
```
Deletes the specified branch from your local repository.

---

## 12. View Commit History
```bash
git log
```
Displays the commit history for your current branch.

---

## 13. Undo Changes Before Staging
```bash
git checkout -- filename
```
Discards changes in the working directory for the specified file.

---

## 14. Reset Staged Changes
```bash
git reset HEAD filename
```
Unstages the specified file while keeping the changes in the working directory.

---

## 15. Revert a Commit
```bash
git revert commit-hash
```
Creates a new commit that reverses the changes from a specific commit.

---

## 16. Set Upstream Branch (First Push)
```bash
git push -u origin branch-name
```
Sets the upstream branch so you can push changes with `git push` in the future.

---

This **Git Basics Cheat Sheet** gives you the essential commands needed for managing Git repositories effectively. Copy it all at once for easy reference during your Git workflows.
