# 🚀 Git Rebase Practice

Welcome to the **Git Rebase Practice** repository! This repo is designed as a hands-on guide to mastering the `git rebase` command. Here, you’ll learn how to work with different branches, handle conflicts, and organize commit histories effectively.

## ✨ Purpose

The purpose of this repository is to help you practice and gain confidence in using Git rebase commands. The exercises in this repo will allow you to:

- Rebase one branch onto another to integrate changes seamlessly
- Resolve merge conflicts that arise during rebasing
- Use **interactive rebasing** to organize, squash, or reorder commits
- Push rebased branches to GitHub and understand when and why to use force-push

## 📋 Repository Structure

This repository has two main branches:

- **`main`**: The primary branch with initial commits
- **`feature-branch`**: A branch with additional commits for rebase practice

## 🛠️ Common Git Rebase Commands

Here are some of the core `git rebase` commands you’ll use in this repo:

### ➡️ Rebase a Branch onto Another Branch

Move the commits from your current branch on top of the specified branch.

```bash
git checkout feature-branch
git rebase main
```

### 🔄 Continue a Rebase after Resolving Conflicts

If conflicts arise during rebasing, resolve them, and then continue the rebase.

```bash
git rebase --continue
```

### 🚫 Abort a Rebase

If you want to cancel the rebase and revert to the previous state, you can abort it.

```bash
git rebase --abort
```

### 🎛️ Interactive Rebase

Use interactive rebase to edit, squash, or reorder commits. Replace `HEAD~N` with the number of commits you want to include in the rebase.

```bash
git rebase -i HEAD~2
```

### ⚠️ Force-Push After Rebasing

After completing a rebase on a shared branch, you’ll often need to force-push to update the remote branch.

```bash
git push -f origin feature-branch
```

> **Note:** Be cautious when force-pushing, especially on shared branches, as it can overwrite others' work.

---

## 📖 Learning Goals

Through these exercises, you’ll become proficient in:

- Integrating changes smoothly across branches
- Maintaining a clean and organized commit history
- Handling real-world scenarios like merge conflicts
- Using interactive rebasing to customize your commit history

## 🎉 Get Started!

1. Clone this repository.
2. Experiment with the commands listed above.
3. Have fun learning and don’t be afraid to make mistakes—they’re a part of the learning process!

---

Happy rebasing! 😊