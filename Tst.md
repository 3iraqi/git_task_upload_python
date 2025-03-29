### 🚀 **Git Cheat Sheet** 🚀  

#### **🔹 Basic Commands**
```sh
git init                     # Initialize a new Git repository
git clone <repo_url>         # Clone a repository
git status                   # Check the status of the working directory
git add <file>               # Stage a specific file
git add .                    # Stage all changes
git commit -m "Message"      # Commit staged changes
git push origin <branch>     # Push commits to remote repo
git pull origin <branch>     # Pull latest changes from remote repo
```

---

#### **🔹 Branching & Merging**
```sh
git branch                   # List all branches
git branch <branch_name>      # Create a new branch
git checkout <branch_name>    # Switch to a branch
git checkout -b <branch_name> # Create and switch to a new branch
git merge <branch_name>       # Merge another branch into the current branch
git branch -d <branch_name>   # Delete a branch
git push origin --delete <branch_name> # Delete a remote branch
```

---

#### **🔹 Remote Repository Management**
```sh
git remote -v                # View remote repositories
git remote add origin <url>  # Add a remote repository
git remote rename old new    # Rename a remote
git remote remove <name>     # Remove a remote
```

---

#### **🔹 Undo Changes**
```sh
git checkout -- <file>        # Discard changes in a file
git reset HEAD <file>         # Unstage a file
git reset --soft HEAD~1       # Undo last commit (keep changes staged)
git reset --hard HEAD~1       # Undo last commit (remove changes)
git revert <commit_id>        # Revert a specific commit
```

---

#### **🔹 Stashing Changes**
```sh
git stash                     # Stash current changes
git stash list                 # Show all stashes
git stash apply                # Apply last stashed changes
git stash drop                 # Delete last stash
git stash pop                  # Apply and remove last stash
```

---

#### **🔹 Viewing History & Logs**
```sh
git log                       # View commit history
git log --oneline --graph      # Compact commit history
git show <commit_id>          # Show details of a commit
git diff                      # View unstaged changes
git diff --staged             # View staged changes
```

---

#### **🔹 Tags (For Versioning)**
```sh
git tag                       # List all tags
git tag -a v1.0 -m "Version 1.0" # Create a tag
git push origin --tags        # Push tags to remote
git tag -d <tag_name>         # Delete a local tag
git push origin :refs/tags/<tag_name> # Delete remote tag
```

---

### **🔥 Pro Tips**
✅ Use `git pull --rebase` instead of `git pull` to avoid unnecessary merge commits.  
✅ Use `git log --graph --decorate --oneline --all` for a clean history view.  
✅ Use `.gitignore` to exclude files from Git tracking.  


tst

