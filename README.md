# Post-Commit Hook Demo
Automatically appends the latest commit message and timestamp to `commit-log.md` after every commit.
1. A `post-commit` hook script is placed in `.git/hooks`.
2. The script captures the commit message and timestamp.
3. It appends this info to `commit-log.md`.
4. when i make a commit,Checks `commit-log.md`.I can see new entry at the bottom.
# Importance of hooks
- Automate repetitive task,
- Improve developer effort by saving time.
