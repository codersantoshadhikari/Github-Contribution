🚀 Git & GitHub Guide: From Beginner to Advanced

Welcome to the ultimate guide for mastering **Git** and **GitHub**! Whether you're a beginner or aiming to level up, this guide provides a comprehensive overview of essential and advanced commands, best practices, and tips for efficient version control and collaboration.

---

## 🧠 What is Git & GitHub?

- **Git**: A distributed version control system to track changes in your code, enabling you to manage versions and collaborate effectively.
- **GitHub**: A cloud-based platform to host Git repositories, collaborate with teams, manage issues, and review code.

**In Simple Terms**: GitHub is like *Google Drive for code*, but with powerful tools to track changes, manage versions, and enable seamless team collaboration.

---

## 💻 About GitHub

GitHub is a leading platform for version control and collaboration, primarily used by software developers to store, manage, track, and collaborate on code projects with ease.

### 🔧 Key Features

- **🔁 Git Version Control**: Built on Git, it tracks code changes, allowing you to revert to previous versions if needed.
- **📁 Repositories (Repos)**: Folders containing your project’s code, files, and complete version history.
- **📝 Commits & Branches**:
  - **Commit**: A snapshot of your code at a specific point in time.
  - **Branch**: A separate line of development for working on new features without affecting the main codebase.
- **🔀 Pull Requests**: Propose changes, collaborate through code reviews, and merge updates into the main branch.
- **🤝 Collaboration**: Work as a team by assigning tasks, discussing bugs, and contributing from different locations.
- **🐞 Issue Tracking**: Create and manage issues to track bugs, improvements, or new feature requests.
- **🌐 GitHub Pages**: Host and publish static websites directly from your GitHub repository.

### 💡 Why Use GitHub?

- 📦 Backup your code in the cloud
- 🌍 Collaborate with teams worldwide
- 💼 Showcase your work to employers or clients
- ⚙️ Integrate with CI/CD tools for automation
- 🚀 Build and contribute to open-source projects

---

## 🚀 Ultimate Git & GitHub Cheat Sheet

### 🔧 Setup & Configuration

```bash
# Install Git
brew install git                     # Mac
sudo apt-get install git             # Linux

# Configure user
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --global core.editor "code --wait"  # VS Code as editor

# View config
git config --list
```

### 📂 Repository Management

```bash
git init                            # Initialize new repo
git clone https://github.com/url    # Clone existing repo
git remote -v                       # View remotes
git remote add origin <url>         # Add remote
git remote set-url origin <new-url> # Change remote URL
```

### 🔄 Basic Workflow

```bash
git status                          # Check changes
git add <file>                      # Stage file
git add .                           # Stage all changes
git commit -m "Descriptive message" # Commit changes
git push -u origin main             # First push
git push                            # Subsequent pushes
git pull                            # Pull latest changes
```

### 🌿 Branching & Merging

```bash
git branch                          # List branches
git branch <name>                   # Create branch
git checkout <branch>               # Switch branch
git checkout -b <new-branch>        # Create & switch
git merge <branch>                  # Merge into current
git branch -d <branch>              # Delete branch
git push origin --delete <branch>   # Delete remote branch
```

### ⏪ Undoing Changes

```bash
git restore <file>                  # Discard unstaged changes
git restore --staged <file>         # Unstage file
git commit --amend                  # Fix last commit
git reset HEAD~1                    # Undo commit, keep changes
git reset --hard HEAD~1             # Undo commit & discard changes
git revert <commit-hash>            # Safe undo for shared commits
```

### 🧰 Advanced Tools

```bash
git stash                           # Save work temporarily
git stash list                      # View stashes
git stash apply                     # Restore most recent stash
git rebase <branch>                 # Reapply commits on top
git cherry-pick <commit-hash>       # Apply specific commit
git log --oneline --graph --all     # Visual commit history
```

### 🤝 GitHub Collaboration

```bash
# Fork workflow
git remote add upstream <original-repo-url>
git fetch upstream
git merge upstream/main

# Pull Requests (via GitHub CLI)
gh pr create --base main --head feature-branch
gh pr view --web
gh pr merge --squash
```

---

## 🔗 Learn More

- GitHub Docs
- Git Basics
- GitHub Pages Guide

---

# 🔥 SMAIT TECHNOLOGY | SMAIT SOFTWARE

*Nepal's Premier Tech Innovation Hub*

## 🏢 Company Overview

📍 **Headquarters**: Pokhara-14, Chauthe, Nepal\
👨‍💻 **Founder & Lead Developer**: Santosh Adhikari (`@CoderSantoshAdhikri`)

### 🌐 Core Focus Areas

| Category | Technologies/Services |
| --- | --- |
| **Web Development** | React, Node.js, Next.js |
| **Mobile Development** | Flutter, React Native |
| **AI/ML Solutions** | Python, TensorFlow, LLMs |
| **Cloud & DevOps** | AWS, Docker, Kubernetes |
| **Cybersecurity** | Pentesting, Secure Architecture |

## 🎯 Why SMAIT?

✔ **Boutique Expertise**: Focused, high-quality deliverables\
✔ **Modern Tech Stack**: Always updated with industry trends\
✔ **Transparent Process**: Agile development with client collaboration\
✔ **Cost-Effective**: Premium solutions at competitive rates

## 📬 Contact Channels

### Primary Contacts

📧 **Business Inquiries**: smaittechnology@gmail.com\
📧 **Technical Consultations**: santoshadhikariofficial@gmail.com

### Digital Presence

🌍 **Portfolio**: santoshadhikari.info.np\
💬 **WhatsApp**: +977 9745999476\
🔗 **LinkedIn**: Connect with Santosh

## 🏆 Our Differentiators

