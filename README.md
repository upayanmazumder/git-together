# Git Together

**Git Together** was a fully hands-on workshop on Git & GitHub conducted by **TAM – The Artificial Intelligence & Machine Learning Club** at **VIT Vellore**.  
The event took place on **6th August 2025** at **SJT Bhagat Singh Gallery**, with full registrations on VTOP and strong participation from freshers, 2nd years, and students across multiple disciplines.  

This repository contains the **slides** and **hands-on exercises** from the session.  

---

## Speakers
- **[Rashmi Nagaraj](https://www.linkedin.com/in/rashmi-nagaraj-a48ab5347/)** – Delivered the opening remarks and introduced the session  
- **[Aadya Singh](https://www.linkedin.com/in/aadya-singh-506047342/)** – Hands-on introduction to version control & Git basics *(Slides 1–12)*  
- **[Upayan Mazumder](https://upayan.dev/)** – Hands-on advanced Git & GitHub workflows *(Slides 13+)*  

---

## Topics Covered

### 🔹 Part 1 – *Aadya (Slides 1–12)*
- The need for **Version Control Systems (VCS)**  
- Tracking changes, collaborating, contributing to open source  
- **GitHub Student Developer Pack** – tools & benefits for students  
- **Git vs GitHub**  
  - Git = version control system  
  - GitHub = hosting & collaboration platform  
- Git installation & setup  
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your@email.com"
  git config --list
  ```

* Key GitHub terminologies: repo, commit, clone, push, pull
* Practiced Git commands in the CLI
* Hands-on:

  * Creating a repository
  * Making first commit
  * Pushing local changes to GitHub

  ```bash
  git remote add origin <repo-url>
  git branch -M main
  git push -u origin main
  ```

---

### 🔹 Part 2 – *Upayan (Slides 13+)*

* **Profile README.md** – building your GitHub profile
* **Contribution graph** – consistency > quantity
* **Pinned repositories** – showcasing your portfolio
* **Branches**

  * Creating & switching branches
  * Safe testing in feature branches (`feat-<feature>`)
  * Merging into main
* **Pull Requests & Merging**

  * Creating PRs on GitHub
  * Collaboration & code review
* **Versioning**

  * Commits = frequent snapshots
  * Versions (tags) = stable milestones
  * Difference between commits vs versions
  * Semantic versioning ([semver.org](https://semver.org/))

  ```bash
  git tag v1.0.0
  git push origin v1.0.0
  ```

---

## Event Details

* **Date:** 6th August 2025
* **Venue:** SJT Bhagat Singh Gallery, VIT Vellore
* **Format:** Fully hands-on workshop

---

## Acknowledgements

Special thanks to:

* **TAM – The Artificial Intelligence & Machine Learning Club** for organizing and supporting the event
* **VIT Vellore** for providing the venue and platform

---

## 📂 Repository Structure

```
index.html     → Demo HTML file used during the workshop
global.css     → Stylesheet for the demo project
.vscode/       → VS Code settings used for Git integration
README.md      → Event overview
```

## Slides

You can download the presentation used in the workshop here:  

[![Download Slides](https://img.shields.io/badge/Download-PPTX-blue?style=for-the-badge&logo=microsoft-powerpoint)](https://github.com/upayanmazumder/git-together/blob/main/GIT%20Together.pptx)

---

## Replay the Hands-On

Follow the same workflow we practiced live:

```bash
# Clone this repository
git clone https://github.com/upayanmazumder/git-together.git
cd git-together

# Configure Git
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

# Create a new branch
git checkout -b feat-demo

# Make changes and commit
git add .
git commit -m "My demo commit"

# Push branch to GitHub
git push origin feat-demo

# Open a Pull Request on GitHub
```

---

## Connect

* [Upayan Mazumder](https://www.linkedin.com/in/upayanmazumder/)
* [Aadya Singh](https://www.linkedin.com/in/aadya-singh-506047342/)
* [Rashmi Nagaraj](https://www.linkedin.com/in/rashmi-nagaraj-a48ab5347/)
* [TAM – The AI & ML Club, VIT](https://www.linkedin.com/company/tam-vit/)
