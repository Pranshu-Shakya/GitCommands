
## 🧑‍💻 One-time Setup for Each Member (Only First Time)

1. **Open VS Code**

2. Open a terminal inside VS Code:

   ```
   Ctrl + `
   ```

3. **Clone the repository**

   ```bash
    git clone https://github.com/Pranshu-Shakya/EcoSphere.git
   ```


4. **Navigate into the project folder**

   ```bash
   cd EcoSphere
   ```

5. **Checkout( to get in your branch ) your personal branch**
   For example, for Pranshu:

   ```bash
   git checkout pranshu
   ```

6. **Start coding in your branch!** 🎯

---

## 🔁 Everyday Workflow (For Each Team Member)

> 💡 Always make sure you are on *your own branch* before making changes.

### 🔍 1. Make sure you're on your own branch

```bash
git checkout your-branch-name
```

Example:

```bash
git checkout pranshu
```

---

### 🧠 2. Pull latest changes from the main branch (optional but good practice)

This avoids conflicts if `main` was updated:

Before start coding run all these commands to get updated if main branch is modified.

```bash
git checkout main
git pull origin main
git checkout your-branch-name
git merge main
```

---

### ✏️ 3. Make your changes in VS Code

Write your code, create new files, edit old ones — whatever your task is.

---

### 💾 4. Stage your changes

```bash
git add .
```

---

### 📝 5. Commit with a meaningful message

```bash
git commit -m "Added login page layout"
```

---

### 🚀 6. Push your code to GitHub

```bash
git push origin your-branch-name
```

---

### 🔀 7. Create a Pull Request (PR)

1. Go to GitHub repo → **Pull Requests** tab.
2. Click **“New pull request”**.
3. Choose:

   * **base**: `main`
   * **compare**: your branch (e.g., `pranshu`)
4. Write a short description and **create the PR**.

---

### ✅ 8. Merge and pull latest after PR approval

Once merged into `main`, all members should:

```bash
git checkout main
git pull origin main
```

---

## 🔄 Optional: If you switch between branches

Before switching, **commit or stash** your current changes:

```bash
git stash
git checkout other-branch
git stash pop
```

---

## 🧰 VS Code Git UI (Optional but Easy)

* Use **Source Control** icon on the sidebar (Git icon)
* Click **+** to stage, type message, click ✓ to commit, then "..." > Push
* You can also check branches and switch easily from the **bottom-left corner**

---

Would you like me to create a **simple `README.md` or folder structure** to get started with the project too?
