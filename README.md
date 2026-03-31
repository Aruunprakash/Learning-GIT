 🚀 Git & GitHub Learning Journey

🧠 Purpose of this Repo

This repository documents my journey of learning Git and GitHub step by step.

📌 What I’ve Learned

### 📅 Day 1:
* Installed and configured Git on macOS
* Connected Git with GitHub
* Basic terminal commands: `cd`, `mkdir`, `ls`, `ls -a`
* Git commands:

  * `git clone`
  * `git status`
  * `git add`
  * `git commit`

### 📅 Day 2:
  * `git push`
    * `git push -u origin main`
  * `git init:-`
    * `git remote add origin`
    * `git remote -v` #version check
    * `git branch`

NOTE: 
I faced certain issue as I cloned again on top of an existing remote repo , i.e already pulled. Worked through it and understood the core ccd oncept more clearly.

### 📅 Day 3

* Workflow:

  * Local Git process:

    * Create repository → Clone → Make changes → Add → Commit → Push

* Git Branches:

  * Used when multiple people work on the same project

* Branch Commands:

  * `git branch` (check current branch)

    * Default branch is `main` or `master`

      * Rename branch:

        * `git branch -m main`
      * Switch to another branch:

        * `git checkout branch-name`
      * Create a new branch:

        * `git checkout -b new-branch`
      * Delete a branch:

        * `git branch -d branch-name`
        * Note: Cannot delete a branch while currently on it

