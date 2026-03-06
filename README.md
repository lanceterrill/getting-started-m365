# 📘 Nebraska.gov · Microsoft 365 Learning Hub

> A complete set of Getting Started guides for Microsoft 365 apps, built for **Nebraska Department of Insurance** employees and hosted on GitHub Pages.

---

## 🌐 Live Site

**[lanceterrill.github.io/m365](https://lanceterrill.github.io/m365)** *(update URL once deployed)*

---

## 📁 File Structure

```
/
├── index.html                          ← Main portal / landing page
├── getting-started-teams.html
├── getting-started-sharepoint.html
├── getting-started-outlook.html
├── getting-started-onedrive.html
├── getting-started-word.html
├── getting-started-excel.html
├── getting-started-powerpoint.html
├── getting-started-planner.html
├── getting-started-todo.html
├── getting-started-forms.html
├── getting-started-powerbi.html
├── getting-started-powerautomate.html
├── getting-started-powerapps.html
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml                  ← GitHub Actions auto-deploy
```

---

## 📚 Guides Included

| App | File | Category |
|---|---|---|
| 💬 Microsoft Teams | `getting-started-teams.html` | Collaboration |
| 🗂️ SharePoint | `getting-started-sharepoint.html` | Collaboration |
| 📧 Outlook | `getting-started-outlook.html` | Productivity |
| ☁️ OneDrive | `getting-started-onedrive.html` | Productivity |
| 📝 Word | `getting-started-word.html` | Productivity |
| 📊 Excel | `getting-started-excel.html` | Productivity |
| 📽️ PowerPoint | `getting-started-powerpoint.html` | Productivity |
| 📋 Planner | `getting-started-planner.html` | Collaboration |
| ✅ To Do | `getting-started-todo.html` | Productivity |
| 📝 Forms | `getting-started-forms.html` | Productivity |
| 📈 Power BI | `getting-started-powerbi.html` | Power Platform |
| ⚡ Power Automate | `getting-started-powerautomate.html` | Power Platform |
| 📱 Power Apps | `getting-started-powerapps.html` | Power Platform |

---

## 🧱 Each Guide Contains

Each guide is a standalone single-file HTML page with 6 sections:

1. **Hero** — App overview and feature highlights
2. **What Is It + 5 Steps** — Getting started walkthrough
3. **Key Features + Pro Tips** — Core capabilities and power-user advice
4. **Keyboard Shortcuts** — Essential shortcuts for faster workflows
5. **What's New** — 2025–2026 updates and Copilot integrations
6. **Further Learning & Resources** — Official Microsoft support, Learn training paths, video tutorials, certifications, and more

---

## 🚀 Deployment

This repo auto-deploys to GitHub Pages via GitHub Actions on every push to `main`.

### Manual Deploy Steps

1. Clone or download this repo
2. Push all files to your GitHub repository's `main` branch
3. In GitHub → **Settings → Pages → Source**, select **GitHub Actions**
4. The workflow in `.github/workflows/deploy.yml` handles the rest
5. Your site will be live at `https://<username>.github.io/<repo-name>/`

### First-Time Setup

```bash
git clone https://github.com/lanceterrill/<repo-name>.git
cd <repo-name>
# Add your files
git add .
git commit -m "Initial deploy: M365 Learning Hub"
git push origin main
```

GitHub Actions will automatically build and deploy within ~1–2 minutes.

---

## ✏️ Making Updates

Each guide is a **self-contained HTML file** — no build tools, no dependencies, no npm.

To update a guide:
1. Edit the relevant `.html` file directly
2. Commit and push to `main`
3. GitHub Actions redeploys automatically

---

## 🎨 Design

- **Fonts:** Barlow Condensed (headings) + Outfit (body)
- **Colors:** Nebraska Navy `#003087` · Nebraska Gold `#FFCD00`
- **Each app** has a unique accent color matching Microsoft's branding
- All pages are fully responsive (mobile, tablet, desktop)
- No JavaScript frameworks, no npm, no build step — pure HTML/CSS/JS

---

## 💬 Support

Questions? Message **Lance Terrill** on Teams:

[💬 Message Lance on Teams](https://teams.microsoft.com/l/chat/0/0?users=lance.terrill@nebraska.gov&message=Hi%20Lance%2C%20I%20have%20a%20question%20about%20the%20M365%20guides!)

---

## 🏛️ Organization

**Nebraska Department of Insurance · IT Division**  
State of Nebraska · Nebraska.gov  
IT Guide Series 2026
