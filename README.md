# 🚀 Git & GitHub Guide

A beginner-friendly guide to learn the basics of **Git** and **GitHub** with commands and examples that i learned during by development journey.

---

## 📌 Git Basics
- Initialize a repository  
  ```bash
  git init
- Check status
  ```bash
  git status
- Stage files
  ```bash
  git add "filename"
- Commit changes (use present tense by convention)
  ```bash
  git commit -m "Add feature"
- View commit history
  ```bash
  git log

---

## 📝 Working with files
- See changes
  ```bash
  git diff filename
- Discard changes & revert file
  ```bash
  git checkout filename

---

## 🙈 Using .gitignore
- Remove files from staging area
  ```bash  
  git rm -r --cached filename
- Add & commit again
  ```bash
  git add .
  git commit -m "Update .gitignore"

---

## 🌍 Remote Repositories
- Add remote repo
  ```bash
  git remote add origin <repo-url>
- Push local repo to remote
  ```bash
  git push -u origin main
- Clone a repo
  ```bash
  git clone <repo-url>

## 🌱 Branching & Merging
- Create a new branch
  ```bash
  git branch feature-branch
- Switch to the new branch
  ```bash
  git checkout feature-branch
- Go back to main
  ```bash
  git checkout main
- Merge branch into main
  ```bash
  git merge feature-branch

---

## 🍴 Forking Workflow
- Clone your forked repository
  ```bash
  git clone <forked-repo-url>
- Modify and push changes
  ```bash
  git push origin main
- Submit a Pull Request (PR) on GitHub

---

## 📚 Summary (Checklist)

- [x] Initialize repo  
- [x] Stage & commit changes  
- [x] View history & diffs  
- [x] Ignore files with `.gitignore`  
- [x] Work with remotes  
- [x] Branch & merge  
- [x] Fork & submit PRs

---

## 🏁 Conclusion

Git and GitHub are essential tools for every developer to manage code efficiently, collaborate with teams, and contribute to open-source projects.  
By mastering the basics—initializing repositories, staging and committing changes, working with branches, handling remotes, and using pull requests—you’ll be able to maintain clean workflows and contribute effectively.  

✨ Keep practicing, explore advanced commands, and soon Git will become second nature! 🚀
