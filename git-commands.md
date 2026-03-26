# 🔥 GitHub / Git Cheat Sheet

## 📁 Repository Setup

| Command                 | Description           | Example                                      |
| ----------------------- | --------------------- | -------------------------------------------- |
| `git init`              | Initialize a new repo | `git init`                                   |
| `git clone`             | Clone remote repo     | `git clone https://github.com/user/repo.git` |
| `git remote add origin` | Add remote repo       | `git remote add origin <url>`                |
| `git remote -v`         | Show remote URLs      | `git remote -v`                              |

---

## 📦 Staging & Commit

| Command          | Description                | Example                          |
| ---------------- | -------------------------- | -------------------------------- |
| `git status`     | Check repo status          | `git status`                     |
| `git add file`   | Add file to staging        | `git add app.py`                 |
| `git add .`      | Add all files              | `git add .`                      |
| `git commit -m`  | Commit changes             | `git commit -m "Initial commit"` |
| `git commit -am` | Add + commit tracked files | `git commit -am "update"`        |

---

## 🚀 Push & Pull

| Command     | Description         | Example                |
| ----------- | ------------------- | ---------------------- |
| `git push`  | Push to remote      | `git push origin main` |
| `git pull`  | Pull + merge        | `git pull origin main` |
| `git fetch` | Fetch without merge | `git fetch origin`     |

---

## 🌿 Branching

| Command             | Description            | Example                   |
| ------------------- | ---------------------- | ------------------------- |
| `git branch`        | List branches          | `git branch`              |
| `git branch name`   | Create branch          | `git branch feature`      |
| `git checkout name` | Switch branch          | `git checkout feature`    |
| `git checkout -b`   | Create + switch        | `git checkout -b feature` |
| `git switch name`   | Switch branch (modern) | `git switch feature`      |
| `git merge`         | Merge branch           | `git merge feature`       |
| `git branch -d`     | Delete branch          | `git branch -d feature`   |

---

## 🔄 Undo Changes

| Command            | Description        | Example                 |
| ------------------ | ------------------ | ----------------------- |
| `git restore file` | Discard changes    | `git restore app.py`    |
| `git reset file`   | Unstage file       | `git reset app.py`      |
| `git reset --hard` | Reset everything   | `git reset --hard HEAD` |
| `git revert`       | Undo commit safely | `git revert HEAD`       |

---

## 📜 Logs & History

| Command             | Description         | Example             |
| ------------------- | ------------------- | ------------------- |
| `git log`           | Show commits        | `git log`           |
| `git log --oneline` | Short log           | `git log --oneline` |
| `git diff`          | Show changes        | `git diff`          |
| `git show`          | Show commit details | `git show <id>`     |

---

## 🔗 GitHub Specific (Remote Work)

| Command                   | Description | Example                   |
| ------------------------- | ----------- | ------------------------- |
| `git push -u origin main` | First push  | `git push -u origin main` |
| `git pull origin branch`  | Pull branch | `git pull origin dev`     |
| `git push origin branch`  | Push branch | `git push origin feature` |

---

## 🧹 Stash (Temporary Save)

| Command           | Description    | Example           |
| ----------------- | -------------- | ----------------- |
| `git stash`       | Save changes   | `git stash`       |
| `git stash list`  | List stash     | `git stash list`  |
| `git stash apply` | Apply stash    | `git stash apply` |
| `git stash pop`   | Apply + delete | `git stash pop`   |

---

## 🏷️ Tags

| Command                | Description | Example                |
| ---------------------- | ----------- | ---------------------- |
| `git tag`              | List tags   | `git tag`              |
| `git tag v1.0`         | Create tag  | `git tag v1.0`         |
| `git push origin v1.0` | Push tag    | `git push origin v1.0` |

---

## ⚙️ Config

| Command                          | Description  | Example                                          |
| -------------------------------- | ------------ | ------------------------------------------------ |
| `git config --global user.name`  | Set username | `git config --global user.name "Ashu"`           |
| `git config --global user.email` | Set email    | `git config --global user.email "you@gmail.com"` |
| `git config --list`              | Show config  | `git config --list`                              |

---

## 💡 Most Important Commands (Interview Focus)

If you remember only these, you’re solid:

```
git clone
git status
git add .
git commit -m "msg"
git push
git pull
git branch
git checkout -b branch_name
git merge
git log --oneline
```


