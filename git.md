# Git interview questions

My own answers, written in my own words.

## 1. What is a branch and why use one?

Key idea: an independent line of work that lets you try changes without touching main.

My answer:

## 2. Merge vs rebase: what is the difference?

Key idea: merge keeps history and adds a merge commit; rebase rewrites commits on top of another branch for a linear history. Never rebase shared branches.

My answer:

## 3. How do you resolve a merge conflict?

Key idea: open the marked files, choose what stays, remove the markers, git add, then commit.

My answer:

## 4. git revert vs git reset: when do you use each?

Key idea: revert creates a new commit that undoes another (safe for shared history); reset moves the branch back and can rewrite history.

My answer:

## 5. What does git stash do?

Key idea: temporarily saves uncommitted changes so you can switch context, then restores them.

My answer:
