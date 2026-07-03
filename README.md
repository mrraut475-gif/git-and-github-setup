# git-and-github-setup for all laptop and desktop
# Git & GitHub Setup Guide

A simple, step-by-step cheatsheet for configuring Git, linking a local project folder to GitHub, and managing the daily update cycle.

---

## 🛠️ Part 1: First-Time Git Configuration
> **Note:** Run these commands inside **Git Bash** only once when you first set up Git on your computer.

### 1. Clear Existing Configuration
Remove any old username or email data stored on your system:
```bash
git config --global --unset user.name
git config --global --unset user.email
git config --global user.name "mrraut475-gif"
git config --global user.email "mrraut475@gmail.com"
git config --list
# Initialize a blank Git repository in your folder
git init

# Set your default local branch name to 'main'
git branch -M main

# Link your local folder to your GitHub repository
git remote add origin [https://github.com/mrraut475-gif/News-Website.git](https://github.com/mrraut475-gif/News-Website.git)
git add .
git commit -m "Your custom commit message here"
git push origin main
