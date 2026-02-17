# 1️ Introduction to Git

## 🔹 What is Git?

**Git** is a **distributed version control system (DVCS)** used to track changes in source code during software development.

It helps developers:

- Track changes in files
    
- Work in teams
    
- Restore previous versions
    
- Manage different features separately
    

Git was created by  
Linus Torvalds in **2005** for managing the development of  
Linux kernel.

---

## 🔹 What is Version Control?

Version Control is a system that:

- Records changes to a file over time
    
- Allows you to go back to previous versions
    
- Shows who made changes and when
    

Example:  
If you write code today and break it tomorrow, Git lets you go back to yesterday’s working version.

---

# 2️Why Git is Important

Before Git:

- Developers shared code using ZIP files 
    
- No proper tracking of changes 
    
- Code conflicts were common 
    

With Git:

- Safe collaboration 
    
- Full history of project 
    
- Multiple people can work together 
    
- Easy backup system 
    

---

# 3️ Key Concepts of Git

##  1. Repository (Repo)

A repository is a project folder that Git tracks.

It contains:

- Project files
    
- Hidden `.git` folder
    
- History of changes
    

There are two types:

|Type|Meaning|
|---|---|
|Local Repository|On your computer|
|Remote Repository|On internet (like GitHub)|

Popular remote platform:  
GitHub

---

## 🔹 2. Working Directory

The folder where you create or edit files.

---

## 🔹 3. Staging Area (Index)

Temporary area where files are prepared before saving.

Think of it like:

> Draft area before final submission.

---

##  4. Commit

A **commit** is a snapshot of your project at a specific time.

Each commit has:

- Unique ID (SHA hash)
    
- Author name
    
- Date & time
    
- Message
    

Example:

`git commit -m "Added login page"`

---

# 4️ Git Architecture

Git works in 3 main areas:

`Working Directory → Staging Area → Repository`

Steps:

1. Modify files
    
2. Add to staging (`git add`)
    
3. Commit (`git commit`)
    

---

# 5️ Installing Git

You can download Git from:  
Git official website.

Check installation:

`git --version`

---

# 6️ Basic Git Commands

## 🔹 Initialize Repository

`git init`

Creates a new Git repository.

---

##  Check Status

`git status`

Shows:

- Modified files
    
- Staged files
    
- Untracked files
    

---

##  Add Files

Add single file:

`git add filename.txt`

Add all files:

`git add .`

---

##  Commit Changes

`git commit -m "Your message"`

---

##  View Commit History

`git log`

Short version:

`git log --oneline`

---

#  Branching in Git

##  What is a Branch?

A branch is a separate line of development.

Default branch name:

`main`

---

##  Create New Branch

`git branch newbranch`

Or create and switch:

`git checkout -b newbranch`

---

##  Switch Branch

`git checkout branchname`

---

##  Delete Branch

`git branch -d branchname`

Force delete:

`git branch -D branchname`

---

# 8️Merging in Git

Merging combines two branches.

Example:

`git checkout main git merge newbranch`

If conflicts happen:

- Git asks you to resolve manually
    
- After fixing:
    

`git add . git commit`

---

# 9️ Remote Repositories

##  Add Remote

`git remote add origin https://github.com/username/repo.git`

---

##  Push Code

`git push origin main`

Uploads local code to GitHub.

---

##  Pull Code

`git pull origin main`

Downloads latest changes.

---

##  Clone Repository

`git clone https://github.com/user/repo.git`

Copies project from GitHub to local system.

---

# 10 Git Workflow Example

Typical workflow:

1. `git clone`
    
2. `git checkout -b feature`
    
3. Make changes
    
4. `git add .`
    
5. `git commit -m "Feature added"`
    
6. `git push`
    
7. Create Pull Request
    
8. Merge
    

---

# 1️ What is Pull Request?

A Pull Request (PR) is used to:

- Request merging of code
    
- Review changes
    
- Discuss improvements
    

Commonly used on  
GitHub.

---

# 2️ Git vs GitHub

|Git|GitHub|
|---|---|
|Software|Platform|
|Works offline|Works online|
|Tracks changes|Hosts repositories|

Git = Tool  
GitHub = Service

---

# 3️ Advantages of Git

✔ Fast  
✔ Distributed  
✔ Secure  
✔ Supports branching  
✔ Open source

---

# 4️ Common Git Errors

###  Merge Conflict

When two branches modify same line.

### Detached HEAD

When you checkout a commit instead of branch.

###  Untracked Files

Files not added to Git.

---

# 6️ Git File Lifecycle

File states:

1. Untracked
    
2. Modified
    
3. Staged
    
4. Committed
    

Lifecycle:

`Untracked → Modified → Staged → Committed`

---

# 7️ Advanced Concepts (Brief)

### 🔹 Rebase

Reapplies commits on top of another base branch.

### 🔹 Cherry-pick

Applies specific commit to another branch.

### 🔹 Stash

Temporarily saves uncommitted changes.

`git stash git stash pop`

---
