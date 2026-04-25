# 🚀 Git & GitHub Learning Journey

## 🧠 Purpose of this Repo

This repository documents my journey of learning Git and GitHub step by step.

---

## 📌 What I’ve Learned

### 📅 Day 1:

* Installed and configured Git on macOS
* Connected Git with GitHub
* Basic terminal commands: `cd`, `mkdir`, `ls`, `ls -a`

**Git commands:**

* `git clone`
* `git status`
* `git add`
* `git commit`

---

### 📅 Day 2:

* `git push`
* `git push -u origin main`

**Git init & remote:**

* `git init`
* `git remote add origin`
* `git remote -v` (version check)
* `git branch`

**Note:**
Faced issues by cloning over an existing repo. Understood the core concept better after fixing it.

---

### 📅 Day 3

**Workflow:**

* Create repository → Clone → Make changes → Add → Commit → Push

**Git Branches:**

* Used when multiple people work on the same project

**Branch Commands:**

* `git branch` (check current branch)

* `git branch -a` (view all branches: local + remote)

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

---

### 📅 Day 4

**Undoing Changes:**

* Case 1: Staged changes (added but not committed)

  * `git reset <filename>`

* Case 2: Undo last commit

  * `git reset HEAD~1`

* Case 3: Undo multiple commits

  * Use `git log` to get commit hash
  * `git reset <commit-hash>`
  * `git reset --hard <commit-hash>` (removes changes completely)

---

**Fork:**

* Fork is a copy of a repository
* Creates a new repo under your account
* Shares code with the original (upstream) repo

**Used for:**

* Contributing to open-source
* Making changes without affecting original repo

---

## 📁 Organizing Files in GitHub (Using Git)

### 🧠 Concept

* GitHub repos are organized using folders
* Git does not track empty folders
* A folder exists only when it contains files

### 📌 Commands

```bash
mkdir MySQL
mv queries.sql MySQL/
git add .
git commit -m "Added MySQL folder"
git push
```
