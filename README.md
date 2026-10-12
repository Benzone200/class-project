# CSC 407: Class Projects

Submission repository for **CSC 407**. Every student submits their assigned project here so the lecturer can review everyone's code in one place.

> You do **not** need an invite. You submit by forking this repo and opening a pull request.

---

## Quick Start

1. **Fork** this repo (button at the top right).
2. **Clone** your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/class-project.git
   cd class-project
   ```
3. **Create your folder** inside `students/`, named:
   ```
   firstname-matricno-projecttitle
   ```
   Example: `students/benjamin-12345-school-fees-system`
4. **Add your project code** and a `README.md` inside that folder (see below).
5. **Commit and push:**
   ```bash
   git add .
   git commit -m "Add project: firstname-matricno-projecttitle"
   git push origin main
   ```
6. **Open a Pull Request** from your fork to this repo. Use the title:
   ```
   Submission: Firstname Lastname - Matric No
   ```

Need more detail? See the step-by-step guide below.

---

## What Goes in Your Project README

Create `students/your-folder/README.md` containing:

- Full name and matric number
- Project title
- Short description (2-3 sentences)
- Tech stack
- How to install and run it
- Screenshots (optional, but helpful)

A ready-made template is in [`students/_TEMPLATE/README.md`](students/_TEMPLATE/README.md). Copy it into your folder and fill it in.

---

## Step-by-Step Guide

### 1. Fork
Click **Fork** at the top right of this page, then **Create fork**. You now have your own copy under your GitHub account.

### 2. Clone and enter the repo
Use the clone command in the Quick Start. You need [Git](https://git-scm.com/downloads) installed.

### 3. Create your folder
Folder names must be lowercase, with no spaces (use hyphens).

```
students/
└── firstname-matricno-projecttitle/
    ├── README.md
    ├── src/
    └── ...your code
```

### 4. Commit and push
Run the commands from the Quick Start. If Git asks you to sign in, use your GitHub username and a [personal access token](https://github.com/settings/tokens) as the password, or sign in through GitHub Desktop.

### 5. Open the Pull Request
Go to your fork on GitHub, click **Contribute → Open pull request**, fill in the template, and submit.

### 6. Updating your submission
Just keep committing and pushing to your fork. Your pull request updates automatically. You do not need to open a new one.

---

## Rules

- **Only edit your own folder.** Pull requests that touch anything outside a single folder under `students/` fail the automatic check.
- **Never commit secrets.** No `.env` files, passwords, API keys, or database credentials.
- **Never commit dependencies or build output.** No `node_modules`, `venv`, `build`, or `dist` folders. Add a `.gitignore` inside your folder.
- **Your project must run** following the instructions in your README.
- **Original work only.** You must be able to explain every part of your code.
- **Submit before the deadline** announced in class.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| `Permission denied` when pushing | You cloned this repo instead of your fork. Re-clone using your own username in the URL. |
| Automatic check failed on my PR | You changed files outside your folder, or touched more than one folder. Undo those changes and push again. |
| My fork is out of date | On your fork's page, click **Sync fork → Update branch**, then `git pull`. |
| Merge conflict | You edited something outside your folder. Sync your fork and move your work back into your own folder. |

Still stuck? Ask in the class group chat.
