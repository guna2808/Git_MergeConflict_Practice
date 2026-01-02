# 🔥 Git Merge Conflict Practice

This repository is created **only to practice Git merge conflicts** and understand how conflicts occur, how to read them, and how to resolve them correctly.

## 🎯 Objective

* Learn why merge conflicts happen
* Practice resolving conflicts manually
* Understand conflict markers in Git
* Gain confidence handling real-world conflicts in team projects

## 🧪 What I Am Practicing

* Creating multiple branches
* Making conflicting changes in the same file
* Merging branches into main
* Identifying merge conflicts
* Resolving conflicts step by step
* Completing the merge process

## 🛠️ Typical Flow for Practice

```bash
git checkout -b feature-branch
git checkout main
git checkout -b bugfix-branch
# make conflicting changes
git merge feature-branch
git status
# resolve conflict
git add .
git commit -m "Resolve merge conflict"
```

## ⚠️ Understanding Conflict Markers

When a conflict occurs, Git shows markers like:

```
<<<<<<< HEAD
code from current branch
=======
code from merging branch
>>>>>>> feature-branch
```

These markers help identify which code belongs to which branch.


## 🧠 What I Am Learning

* Conflicts are normal in team development
* Git does not decide which code is correct
* Developers must manually resolve conflicts
* Proper communication and small commits reduce conflicts

## ✅ Practice Status

🚧 Actively practicing merge conflicts

---

✨ Making mistakes intentionally to master Git merge conflict resolution.
