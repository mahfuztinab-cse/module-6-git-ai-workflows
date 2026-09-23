# Module 6: Version Control with Git & AI Workflows

**Student:** Mahfuz Tinab  
**GitHub:** [mahfuztinab-cse](https://github.com/mahfuztinab-cse)  
**Course:** AI-Driven Software Quality Assurance

---

## 📌 Assignment Overview

এই module এ আমরা **Git** এবং **GitHub** এর সম্পূর্ণ workflow শিখেছি এবং **AI** কিভাবে version control এ সাহায্য করে সেটা practice করেছি। Repository management, branching, commit, push, pull, merge — সব concept cover করা হয়েছে।

## 📂 Files in this Repository

assignment-6/
├── git-commands/
│ └── cheatsheet.md # All essential Git commands
├── ai-workflow/
│ ├── ai-in-git.md # AI in Git workflows
│ └── reflection.md # My learning reflection
└── screenshots/ # Screenshots

---

## 🛠️ Tools & Technologies Used

- **Git** — Version control
- **GitHub** — Remote repository
- **VS Code** — Code editor with Git integration
- **Claude AI** — AI assistance

## 📚 Key Learnings

1. Git vs GitHub এর পার্থক্য
2. Repository তৈরি, clone, push, pull
3. Commit, branch, merge
4. Conflict resolution
5. AI-assisted commit messages
6. AI-powered code review
7. GitHub Pull Request workflow

## 🔄 Git Workflow (3 Stages)
Working Directory → Staging Area → Local Repo → Remote (GitHub)
↓ ↓ ↓ ↓
git add . git commit git push GitHub


## 🤖 AI in Git Workflow

| Task | AI Help |
|------|---------|
| Commit message | Generate meaningful messages |
| Code review | Detect bugs before commit |
| Conflict resolution | Suggest best resolution |
| PR description | Auto-generate from commits |
| Branch naming | Suggest conventions |

## 📋 Git Commands Used

```bash
# Setup
git config --global user.name "Mahfuz Tinab"
git config --global user.email "mahfuztinab780@gmail.com"

# Daily workflow
git status
git add .
git commit -m "message"
git push origin main

# Clone and pull
git clone <url>
git pull origin main

# Branching
git checkout -b feature-name
git merge feature-name

# Checking
git log --oneline
git diff
