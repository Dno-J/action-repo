## ⚙️ GitHub Actions Testbed

This repository was created as part of a technical assignment for **TechStax** to demonstrate proficiency with **GitHub Actions**, webhook simulation, and CI/CD workflows. It includes sample trigger files and IDE configuration used during development and testing.

---

## 📁 Project Structure

```
action-repo/
├── .idea/                       # IntelliJ/PyCharm project settings
├── pr_test.txt                  # Pull request simulation file
├── webhook-test.txt             # Webhook simulation file
├── README.md                    # Project documentation
```

---

## 🚀 How to Use (Example Git Workflow)

This repo simulates GitHub Actions triggers using standard Git operations:

```bash
# Create a feature branch
git checkout -b feature/update-readme

# Commit changes
git add README.md
git commit -m "docs: update README with demo walkthrough instructions"

# Push to remote
git push origin feature/update-readme

# Open a pull request → triggers 'pull_request' event
# Merge into main → triggers 'push' event
```

Used `pr_test.txt` and `webhook-test.txt` to simulate different triggers.

---

## 🎯 Features

- ✅ GitHub Actions workflow triggered on push/PR  
- ✅ Manual trigger files for testing  
- ✅ IDE project settings included for inspection and version control

---

## 🙌 Credits

Developed by **Dino** as part of a technical interview assignment for **TechStax**, showcasing automation workflows and GitHub integration.
