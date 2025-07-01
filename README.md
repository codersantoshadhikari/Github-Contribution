
🚀 Git & GitHub Guide: From Beginner to Advanced
Welcome to the ultimate guide for mastering Git and GitHub! Whether you're just starting or looking to level up, this guide covers essential and advanced commands, best practices, and tips for efficient version control and collaboration.

# 💻 About GitHub

GitHub is a platform for version control and collaboration, primarily used by software developers. It allows you to store, manage, track, and collaborate on code projects with ease.

---

## 🧠 In Simple Terms

GitHub is like **Google Drive for code**, but with powerful tools that help teams track changes, manage versions, and work together efficiently.

---

## 🔧 Key Features

### 🔁 Git Version Control
GitHub is built on **Git** — a version control system that tracks changes in your code so you can easily revert to previous versions if needed.

### 📁 Repositories (Repos)
Repositories are folders that contain your project’s code, files, and complete version history.

### 📝 Commits & Branches
- **Commit**: A snapshot of your code at a specific point in time.
- **Branch**: A separate line of development that lets you work on new features without affecting the main codebase.

### 🔀 Pull Requests
Propose changes, collaborate through code reviews, and merge updates into the main branch with pull requests.

### 🤝 Collaboration
Work as a team by assigning tasks, discussing bugs, and contributing together — all from different locations.

### 🐞 Issue Tracking
Create and manage issues to track bugs, improvements, or new feature requests.

### 🌐 GitHub Pages
Host and publish static websites directly from your GitHub repository.

---

## 💡 Why Use GitHub?

- 📦 Backup your code in the cloud  
- 🌍 Collaborate with teams worldwide  
- 💼 Showcase your work to employers or clients  
- ⚙️ Integrate with CI/CD tools for automation  
- 🚀 Build and contribute to open source projects  

---

## 🔗 Learn More

- [GitHub Docs](https://docs.github.com)
- [Git Basics](https://git-scm.com/book/en/v2)
- [GitHub Pages Guide](https://pages.github.com/)

------ 


# 🚀 Git & GitHub Guide (Beginner to Advanced)

This guide covers essential and advanced Git & GitHub commands to help you manage code, collaborate, and deploy efficiently.

---

## 🧠 What is Git & GitHub?

- **Git**: Distributed version control system to track changes in your code.
- **GitHub**: A cloud platform to host Git repositories, collaborate with teams, manage issues, and review code.

# 🚀 Ultimate Git & GitHub Cheat Sheet

## 🔧 Setup & Configuration
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

📂 Repository Management
git init                            # Initialize new repo
git clone https://github.com/url    # Clone existing repo
git remote -v                       # View remotes
git remote add origin <url>         # Add remote
git remote set-url origin <new-url> # Change remote URL


🔄 Basic Workflow
git status                          # Check changes
git add <file>                      # Stage file
git add .                           # Stage all changes
git commit -m "Descriptive message" # Commit changes
git push -u origin main             # First push
git push                            # Subsequent pushes
git pull                            # Pull latest changes



🌿 Branching & Merging

git branch                          # List branches
git branch <name>                  # Create branch
git checkout <branch>              # Switch branch
git checkout -b <new-branch>       # Create & switch
git merge <branch>                 # Merge into current
git branch -d <branch>             # Delete branch
git push origin --delete <branch>  # Delete remote branch

⏪ Undoing Changes
git restore <file>                 # Discard unstaged changes
git restore --staged <file>        # Unstage file
git commit --amend                 # Fix last commit
git reset HEAD~1                   # Undo commit, keep changes
git reset --hard HEAD~1           # Undo commit & discard changes
git revert <commit-hash>          # Safe undo for shared commits


🧰 Advanced Tools
git stash                          # Save work temporarily
git stash list                     # View stashes
git stash apply                   # Restore most recent stash
git rebase <branch>               # Reapply commits on top
git cherry-pick <commit-hash>     # Apply specific commit
git log --oneline --graph --all   # Visual commit history

🤝 GitHub Collaboration

# Fork workflow
git remote add upstream <original-repo-url>
git fetch upstream
git merge upstream/main

# Pull Requests (via GitHub CLI)
gh pr create --base main --head feature-branch
gh pr view --web
gh pr merge --squash


# 🔥 SMAIT TECHNOLOGY | SMAIT SOFTWARE  

📍 **Headquarters**: Pokhara-14, Chauthe, Nepal  
👨‍💻 **Founder & Lead Developer**: [Santosh Adhikari](https://www.linkedin.com/in/santosh-adhikari-b24324265/) (`@CoderSantoshAdhikri`)  

---

## 🚀 **About Us**  
**SMAIT TECHNOLOGY** (and its software division **SMAIT SOFTWARE**) is a **Nepal-based tech innovator** specializing in:  
- **Custom Software Development** (Web, Mobile, Desktop)  
- **AI/ML & Cloud Solutions**  
- **DevOps & Cybersecurity**  
- **UI/UX Design & Digital Transformation**  

🔹 **Mission**: *"Delivering scalable tech solutions to empower businesses globally."*  

---

## 🌟 **Why Choose Us?**  
✅ **Elite Team**: Led by **Santosh Adhikari**, a passionate technologist.  
✅ **Cutting-Edge Tech**: Modern stacks (React, Node.js, Python, Flutter, AWS).  
✅ **Client-First Approach**: Tailored, agile, and transparent workflows.  

---

## 📞 **Get In Touch**  
📧 **Emails**:  
- **Official**: [smaittechnology@gmail.com](mailto:smaittechnology@gmail.com)  
- **Founder**: [santoshadhikariofficial@gmail.com](mailto:santoshadhikariofficial@gmail.com)  

🌐 **Portfolio**: [santoshadhikari.info.np](https://santoshadhikari.info.np)  
📱 **WhatsApp**: [+977 9745999476](https://wa.me/9779745999476)  
💼 **LinkedIn**: [Santosh Adhikari](https://www.linkedin.com/in/santosh-adhikari-b24324265/)  

---

### 🛠 **Powered by Code, Driven by Vision**  
© 2024 **SMAIT TECHNOLOGY** | **SMAIT SOFTWARE**  
