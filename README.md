# 📌 Essential & Advanced Git Commands with Examples

This document provides a **comprehensive guide** to the **most commonly used** Git commands, including **basic**, **intermediate**, and **advanced** commands to help you effectively manage your repositories.

---

## 🚀 Essential Git Commands

### 1️⃣ `git init`
- **Use case**: Initialize a new Git repository.
- **Example**:
  ```bash
  git init
  ```

### 2️⃣ `git clone`
- **Use case**: Clone an existing repository.
- **Example**:
  ```bash
  git clone <repository-url>
  ```

### 3️⃣ `git add`
- **Use case**: Stage changes for commit.
- **Example**:
  ```bash
  git add <file-name>
  git add .  # Add all changes
  ```

### 4️⃣ `git commit`
- **Use case**: Save changes to the repository.
- **Example**:
  ```bash
  git commit -m "Your commit message here"
  ```

### 5️⃣ `git status`
- **Use case**: Show the state of the working directory and staging area.
- **Example**:
  ```bash
  git status
  ```

### 6️⃣ `git log`
- **Use case**: View commit history.
- **Example**:
  ```bash
  git log --oneline --graph
  ```

### 7️⃣ `git branch`
- **Use case**: List, create, or delete branches.
- **Examples**:
  ```bash
  git branch  # List all branches
  git branch <new-branch>  # Create a new branch
  git branch -d <branch-name>  # Delete a branch
  ```

### 8️⃣ `git checkout`
- **Use case**: Switch to a different branch.
- **Example**:
  ```bash
  git checkout <branch-name>
  ```

### 9️⃣ `git merge`
- **Use case**: Merge one branch into another.
- **Example**:
  ```bash
  git merge <branch-name>
  ```

### 🔟 `git pull`
- **Use case**: Fetch and merge changes from a remote repository.
- **Example**:
  ```bash
  git pull origin main
  ```

### 1️⃣1️⃣ `git push`
- **Use case**: Push local commits to a remote repository.
- **Example**:
  ```bash
  git push origin main
  ```

### 1️⃣2️⃣ `git remote`
- **Use case**: Manage remote connections.
- **Example**:
  ```bash
  git remote -v  # View remote URLs
  git remote add origin <repository-url>
  ```

### 1️⃣3️⃣ `git fetch`
- **Use case**: Fetch changes from the remote repository without merging.
- **Example**:
  ```bash
  git fetch origin
  ```

### 1️⃣4️⃣ `git reset`
- **Use case**: Undo changes.
- **Examples**:
  ```bash
  git reset --soft HEAD~1  # Undo last commit (keep changes staged)
  git reset --hard HEAD~1  # Undo last commit (discard changes)
  ```

### 1️⃣5️⃣ `git rebase`
- **Use case**: Reapply commits on top of another base commit.
- **Example**:
  ```bash
  git rebase main
  ```

### 1️⃣6️⃣ `git stash`
- **Use case**: Temporarily save changes.
- **Example**:
  ```bash
  git stash
  git stash pop  # Apply stashed changes
  ```

### 1️⃣7️⃣ `git tag`
- **Use case**: Create version tags.
- **Example**:
  ```bash
  git tag v1.0.0
  git push origin v1.0.0
  ```

### 1️⃣8️⃣ `git diff`
- **Use case**: Show differences between commits.
- **Example**:
  ```bash
  git diff
  ```

### 1️⃣9️⃣ `git revert`
- **Use case**: Undo a commit while keeping history.
- **Example**:
  ```bash
  git revert <commit-hash>
  ```

### 2️⃣0️⃣ `git cherry-pick`
- **Use case**: Apply a specific commit from one branch to another.
- **Example**:
  ```bash
  git cherry-pick <commit-hash>
  ```

---

## 🚀 Advanced Git Commands

### 2️⃣1️⃣ `git bisect`
- **Use case**: Find a bug by binary search.
- **Example**:
  ```bash
  git bisect start
  git bisect bad
  git bisect good <commit-hash>
  ```

### 2️⃣2️⃣ `git reflog`
- **Use case**: View reference logs for HEAD movements.
- **Example**:
  ```bash
  git reflog
  ```

### 2️⃣3️⃣ `git blame`
- **Use case**: Show last modification for each line of a file.
- **Example**:
  ```bash
  git blame filename
  ```

### 2️⃣4️⃣ `git show`
- **Use case**: Display information about a commit.
- **Example**:
  ```bash
  git show <commit-hash>
  ```

### 2️⃣5️⃣ `git clean`
- **Use case**: Remove untracked files.
- **Example**:
  ```bash
  git clean -f
  ```

### 2️⃣6️⃣ `git cherry`
- **Use case**: Show unmerged commits.
- **Example**:
  ```bash
  git cherry -v main feature-branch
  ```

### 2️⃣7️⃣ `git commit --amend`
- **Use case**: Modify the last commit.
- **Example**:
  ```bash
  git commit --amend -m "Updated commit message"
  ```

### 2️⃣8️⃣ `git worktree`
- **Use case**: Manage multiple working trees.
- **Example**:
  ```bash
  git worktree add ../new-feature-branch feature-branch
  ```

### 2️⃣9️⃣ `git archive`
- **Use case**: Create a compressed archive of a repository.
- **Example**:
  ```bash
  git archive --format=zip HEAD > repo.zip
  ```

---

## 🎯 Conclusion
These Git commands cover **everything from basics to advanced techniques**, making you proficient in version control. 🚀
 
🔹 **Happy Coding!** 😃

