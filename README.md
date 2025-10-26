<div style="text-align: center;">
  <img src="images/github-portfolio-db-series.png" alt="git init" width="33%">
</div>

# 🧠 Git Kata Series – Beginner (01–10)

Welcome to **Git Kata**, a hands-on series of small, focused exercises designed to build real Git intuition.  
Each kata lives in its own repository and can be practiced independently or as part of the complete series.

---

## ⚙️ How to Clone

Clone **all katas** (with submodules):

```bash
git clone --recurse-submodules git@github.com:pgurnig/git-kata.git
```

Or clone **a single kata**:

```bash
git clone git@github.com:pgurnig/git-kata-01-the-forgotten-file.git
```

---

## 📘 Series Overview

| #  | Kata                       | Description                                                                                  | GitHub Link |
|----|----------------------------|----------------------------------------------------------------------------------------------|-------------|
| 01 | **The Forgotten File**     | Forget to add a file before committing; learn `git add` and `git commit --amend`.           | [git-kata-01-the-forgotten-file](https://github.com/pgurnig/git-kata-01-the-forgotten-file) |
| 02 | **The Misnamed Commit**    | Fix an incorrect commit message using `git commit --amend`.                                  | [git-kata-02-the-misnamed-commit](https://github.com/pgurnig/git-kata-02-the-misnamed-commit) |
| 03 | **The Unwanted File**      | Stop tracking unwanted files with `.gitignore` and `git rm --cached`.                        | [git-kata-03-the-unwanted-file](https://github.com/pgurnig/git-kata-03-the-unwanted-file) |
| 04 | **The Missing Changes**    | Use `git stash` to save and recover uncommitted work.                                        | [git-kata-04-the-missing-changes](https://github.com/pgurnig/git-kata-04-the-missing-changes) |
| 05 | **The Branch That Got Away** | Move commits from the wrong branch using `git cherry-pick`.                                  | [git-kata-05-the-branch-that-got-away](https://github.com/pgurnig/git-kata-05-the-branch-that-got-away) |
| 06 | **The Diverged Branch**    | Handle divergence and conflicts with `git pull --rebase`.                                    | [git-kata-06-the-diverged-branch](https://github.com/pgurnig/git-kata-06-the-diverged-branch) |
| 07 | **The Deleted Work**       | Recover lost commits or branches using `git reflog`.                                         | [git-kata-07-the-deleted-work](https://github.com/pgurnig/git-kata-07-the-deleted-work) |
| 08 | **The Accidental Push**    | Safely undo a bad push with `git revert`.                                                    | [git-kata-08-the-accidental-push](https://github.com/pgurnig/git-kata-08-the-accidental-push) |
| 09 | **The Merge Mayhem**       | Resolve merge conflicts manually and commit cleanly.                                         | [git-kata-09-the-merge-mayhem](https://github.com/pgurnig/git-kata-09-the-merge-mayhem) |
| 10 | **The Clean Slate**        | Tidy your repo with `git branch -d`, `git prune`, and `git gc`.                              | [git-kata-10-the-clean-slate](https://github.com/pgurnig/git-kata-10-the-clean-slate) |

---

## 🧩 About This Series

Each kata:
- Lives in its **own GitHub repo** for isolated practice.
- Is also included as a **submodule** here for convenient cloning.
- Focuses on one Git concept, with examples that simulate realistic mistakes and fixes.

You can explore them in sequence or jump to topics that interest you.

---

## 💬 Contributing

Ideas for additional katas or improvements are always welcome.  
Open an issue or submit a pull request to **git-kata**.

---

## 📜 License

MIT License © Paul Gurnig
