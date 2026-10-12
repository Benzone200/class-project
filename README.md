# Class Projects Submission Repository

This repository is where every student submits their project code for review by our lecturer.

**Course:** CSC3xx (replace with course code)
**Lecturer:** (replace with lecturer's name)
**Session:** 2026/2027

---

## How to Submit Your Project

You do **not** need to be invited. Just follow these steps.

### 1. Fork this repository
Click the **Fork** button at the top right of this page. This creates your own copy under your GitHub account.

### 2. Clone your fork
```bash
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME
```

### 3. Create your project folder
Inside the `students/` folder, create a folder named like this:

```
firstname-matricno-projecttitle
```

Example: `students/benjamin-12345-school-fees-system`

Put **all your project files** inside this folder. Do not touch anyone else's folder.

### 4. Add a README for your project
Inside your folder, add a `README.md` containing:
- Your full name and matric number
- Project title
- A short description (2-3 sentences)
- Tech stack used
- How to run the project

### 5. Commit and push
```bash
git add .
git commit -m "Add project: firstname-matricno-projecttitle"
git push origin main
```

### 6. Open a Pull Request
Go to your fork on GitHub, click **Contribute**, then **Open pull request**. Use this title format:

```
Submission: Firstname Lastname - Matric No
```

---

## Rules

- One folder per student. Only edit your own folder.
- Do not commit `node_modules`, `.env` files, passwords, or API keys. Add a `.gitignore`.
- Make sure your project runs before you submit.
- You can keep pushing updates to your fork. Your pull request updates automatically.
- Do not delete or modify other students' work.

## Folder Structure

```
.
├── README.md
└── students/
    ├── firstname-matricno-projecttitle/
    │   ├── README.md
    │   └── ...your code
    └── ...
```

## Need Help?

Ask in the class group chat before the submission deadline.
