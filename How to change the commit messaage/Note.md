To change the last commit message in Git, follow these steps:

---

### 1. If the commit has not been pushed:
Use the `git commit --amend` command to edit the last commit message:

```bash
git commit --amend -m "New commit message"
```

This opens the last commit for editing. The new message replaces the old one.

---

### 2. If the commit has already been pushed:
If the commit is already pushed to a shared branch, you need to force-push the amended commit. 

1. Amend the last commit message:
   ```bash
   git commit --amend -m "New commit message"
   ```

2. Force-push the changes:
   ```bash
   git push --force
   ```

---

### Important Notes:
- **Collaboration Warning**: Force-pushing can overwrite others' work if they are working on the same branch. Inform your team before proceeding.
- **Use with Care**: Avoid using `--force` on shared branches unless absolutely necessary.

Would you like a detailed explanation or steps to handle potential conflicts?
