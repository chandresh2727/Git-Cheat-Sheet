# 🚀 Essential Git Commands with Examples

This README provides a **quick reference** to the **20 most commonly used Git commands**, along with their **use cases** and **examples**.

---

## 1️⃣ git init
- **Use case**: Initialize a new Git repository.
- **Example**:
  ```bash
  git init
  ```

---

## 2️⃣ git clone
- **Use case**: Clone an existing repository from a remote source.
- **Example**:
  ```bash
  git clone https://github.com/username/repository.git
  ```

---

## 3️⃣ git status
- **Use case**: Check the status of changes in the working directory.
- **Example**:
  ```bash
  git status
  ```

---

## 4️⃣ git add
- **Use case**: Stage changes for commit.
- **Example**:
  ```bash
  git add file.txt         # Stage a single file
  git add .                # Stage all changes
  ```

---

## 5️⃣ git commit
- **Use case**: Commit staged changes with a descriptive message.
- **Example**:
  ```bash
  git commit -m "Added new feature"
  ```

---

## 6️⃣ git log
- **Use case**: View commit history.
- **Example**:
  ```bash
  git log
  ```

---

## 7️⃣ git branch
- **Use case**: List, create, or delete branches.
- **Example**:
  ```bash
  git branch feature-branch  # Create a new branch
  git branch                 # List all branches
  ```

---

## 8️⃣ git checkout
- **Use case**: Switch between branches.
- **Example**:
  ```bash
  git checkout feature-branch
  ```

---

## 9️⃣ git merge
- **Use case**: Merge changes from one branch into another.
- **Example**:
  ```bash
  git merge feature-branch
  ```

---

## 🔟 git pull
- **Use case**: Fetch changes from a remote repository and merge them into the local branch.
- **Example**:
  ```bash
  git pull origin main
  ```

---

## 1️⃣1️⃣ git push
- **Use case**: Push local commits to a remote repository.
- **Example**:
  ```bash
  git push origin main
  ```

---

## 1️⃣2️⃣ git remote
- **Use case**: Manage remote repositories.
- **Example**:
  ```bash
  git remote -v             # List remote repositories
  git remote add origin URL # Add a remote repository
  ```

---

## 1️⃣3️⃣ git stash
- **Use case**: Temporarily save changes without committing.
- **Example**:
  ```bash
  git stash
  git stash pop             # Apply the stashed changes
  ```

---

## 1️⃣4️⃣ git rebase
- **Use case**: Reapply commits on top of another base branch.
- **Example**:
  ```bash
  git rebase main
  ```

---

## 1️⃣5️⃣ git reset
- **Use case**: Undo changes by resetting the commit history.
- **Example**:
  ```bash
  git reset --hard HEAD~1   # Reset the last commit
  ```

---

## 1️⃣6️⃣ git revert
- **Use case**: Create a new commit that undoes a previous commit.
- **Example**:
  ```bash
  git revert commit_hash
  ```

---

## 1️⃣7️⃣ git diff
- **Use case**: Show differences between files.
- **Example**:
  ```bash
  git diff HEAD
  ```

---

## 1️⃣8️⃣ git tag
- **Use case**: Create version tags.
- **Example**:
  ```bash
  git tag v1.0.0
  git push origin v1.0.0
  ```

---

## 1️⃣9️⃣ git cherry-pick
- **Use case**: Apply a specific commit from another branch.
- **Example**:
  ```bash
  git cherry-pick commit_hash
  ```

---

## 2️⃣0️⃣ git config
- **Use case**: Configure Git settings.
- **Example**:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```

---

### 🎯 **Conclusion**
This guide provides **20 essential Git commands** to streamline your workflow. Mastering these will help you efficiently manage your **repositories, branches, commits, and merges**.

> Keep coding and happy Git-ing! 🚀
