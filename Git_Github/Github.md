# 1️ Introduction to GitHub

##  What is GitHub?

**GitHub** is a **web-based platform** that allows developers to store, manage, and collaborate on code using Git.

It is built on top of  
Git.

In simple words:

> Git = Tool to track code  
> GitHub = Website to store and share Git projects
---

# 2️ Why GitHub is Important

Before GitHub:
- Sharing code was difficult
    
- No proper collaboration system
    
- Hard to track team contributions
With GitHub:
- Code is stored online 
    
- Teams can work together 
    
- Projects have backup 
    
- Open-source projects are accessible 
It is widely used in:
- Web development
    
- App development
    
- Open-source software
    
- Team projects
---

# 3️ Key Features of GitHub

##  1. Repository (Repo)

A repository is a project folder stored on GitHub.

It contains:

- Code files
    
- Commit history
    
- Branches
    
- Pull requests
    

Repositories can be:

|Type|Meaning|
|---|---|
|Public|Anyone can see|
|Private|Only selected users|

---

##  2. Branches

Branches allow you to:

- Work on new features
    
- Fix bugs
    
- Experiment safely
    

Default branch:

`main`

---

##  3. Pull Requests (PR)

A Pull Request is used to:

- Suggest changes
    
- Review code
    
- Merge branches
    

PR helps teams discuss changes before merging.

---

# 4 Creating a Repository

Steps:

1. Login to GitHub
    
2. Click **New Repository**
    
3. Enter repository name
    
4. Choose public or private
    
5. Click Create
    

After creation, GitHub provides commands to connect local Git.

---

# 5 Connecting Local Git to GitHub

Add remote:

`git remote add origin https://github.com/username/repo.git`

Push project:

`git push -u origin main`

Pull updates:

`git pull origin main`

---

# 6 GitHub Workflow (Team Project)

Typical workflow:

1. Clone repository
    
2. Create branch
    
3. Make changes
    
4. Commit
    
5. Push branch
    
6. Create Pull Request
    
7. Review & Merge
    

This system helps avoid conflicts.

---

# 7 GitHub Actions

GitHub Actions allows:

- Automatic testing
    
- Continuous Integration (CI)
    
- Deployment
    

Example:

- When code is pushed → Automatically run tests
---

# 1️ Open Source and GitHub

GitHub is the largest platform for:

- Open-source projects
    
- Community contributions
    

Famous open-source projects hosted on GitHub include:

- VS Code
---

# 2️ GitHub vs Git

|Git|GitHub|
|---|---|
|Software|Platform|
|Works offline|Works online|
|Tracks file changes|Stores & shares projects|

---

# 3️ Advantages of GitHub

✔ Cloud storage  
✔ Team collaboration  
✔ Project management tools  
✔ Open-source contribution  
✔ Free public repositories

---

# 4️ Common GitHub Terms

|Term|Meaning|
|---|---|
|Clone|Copy repo to local|
|Fork|Copy repo to your account|
|Star|Bookmark repository|
|Watch|Get notifications|
|Merge|Combine branches|

---

# 5️ Security in GitHub

GitHub provides:

- Two-factor authentication
    
- Private repositories
    
- Branch protection rules
    

Never upload:

- Passwords
    
- API keys
    
- Secret files
---

# 6 Real-Life Example

Suppose your team is building a website:

- You work on backed
    
- Friend works on fronted
    
- Another teammate designs UI
    

Each creates separate branches.  
After finishing → Create Pull Request → Merge into main.

This keeps project organized.

---
