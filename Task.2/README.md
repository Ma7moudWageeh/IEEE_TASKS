# README.md

---

# Create and Push a Git Repository to GitHub

This tutorial explains the steps I followed to create a **local Git repository**, add a **README.md file**, and push the project to **GitHub**.

---

## 1. Create a Project Folder

First, create a new folder for the project and navigate into it.

```bash
mkdir my-first-repo
cd my-first-repo
```

---

## 2. Initialize a Git Repository

Initialize Git inside the folder.

```bash
git init
```

This creates a hidden `.git` directory that allows Git to track changes.

---

## 3. Create a README.md File

Create a README file that will contain project documentation.

```bash
touch README.md
```

You can open it and add content explaining the project.

---

## 4. Add the File to the Staging Area

Stage the README file so Git can track it.

```bash
git add README.md
```

---

## 5. Make the First Commit

Save the changes in the repository history.

```bash
git commit -m "Initial commit: add README file"
```

---

## 6. Create a Repository on GitHub

1. Go to GitHub.
2. Click **New Repository**.
3. Enter the repository name.
4. Click **Create repository**.

Do not initialize it with a README because we already created one locally.

---

## 7. Add the GitHub Repository as a Remote

Link the local repository with the GitHub repository.

```bash
git remote add origin https://github.com/USERNAME/my-first-repo.git
```

---

## 8. Push the Repository to GitHub

Upload the project to GitHub.

```bash
git branch -M main
git push -u origin main
```

The `-u` option sets the remote branch as the default for future pushes.

---

## 9. Verify the Repository

Go to the GitHub repository page and confirm that the **README.md** file appears.

---

## Summary of Commands

```bash
mkdir my-first-repo
cd my-first-repo
git init
touch README.md
git add README.md
git commit -m "Initial commit"
git remote add origin https://github.com/USERNAME/my-first-repo.git
git branch -M main
git push -u origin main
```

---