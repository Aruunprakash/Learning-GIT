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

### 📅 Day 4

* Undoing Changes:

  * Case 1: Staged changes (added but not committed)

    * `git reset <filename>`

  * Case 2: Undo last commit

    * `git reset HEAD~1`

  * Case 3: Undo multiple commits

    * Use `git log` to get commit hash
    * Undo changes:

      * `git reset <commit-hash>`
      * `git reset --hard <commit-hash>` (removes changes completely)

* Fork:

  * Fork is a copy of a repository
  * It creates a new repository under your account
  * It shares code and visibility with the original (upstream) repository
  * Commonly used for:

    * Contributing to open-source projects
    * Making changes without affecting the original repository

## 📁 Organizing Files in GitHub (Using Git)

### 🧠 Concept
- GitHub repositories are organized using **folders (directories)**
- Git does **not track empty folders**
- A folder exists only when it contains files

# query to create folder and adding files to it

- mkdir MySQL
- mv queries.sql MySQL/
- git add .
- git commit -m "Added MySQL folder"
- git push


