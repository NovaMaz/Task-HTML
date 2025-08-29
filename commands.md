
# Git & Linux Basic Commands

This file contains some of the most commonly used **Git** and **Linux** commands, along with short explanations.  
Useful when setting up a new project or working with repositories.

---

## 🚀 Git Commands

### 1. Initialize, Commit, and Push Code
```bash
git add .
````

> Stages (adds) all the files in the current directory to the staging area.

```bash
git commit -m "Message"
```

> Saves (commits) the staged changes with a descriptive message.
> Think of it as taking a **snapshot** of your project.

```bash
git push origin main
```

> Pushes your committed changes to the remote repository (e.g., GitHub) on the **main** branch.

---

## 📂 Linux Commands

### 1. File & Directory Management

```bash
ls
```

> Lists the files and folders in the current directory.

```bash
pwd
```

> Prints the **current working directory** (the folder you are currently in).

```bash
cd <directory-name>
```

> Changes the current directory to the specified one.

```bash
cd ..
```

> Moves **one step back** (to the parent directory).

---

## ✅ Quick Notes

* Always use clear commit messages (e.g., `"Fixed login bug"` instead of `"update"`).
* Use `git status` frequently to check what’s staged, committed, or untracked.
* `git pull origin main` before pushing ensures your local repo is up-to-date.
