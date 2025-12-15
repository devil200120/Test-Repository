# My Git Workflow

## Daily Development Workflow

1. **Start work**
   ```bash
   git status          # Check current state
   git pull            # Get latest changes                                     Make changes

Edit files
Test changes
Stage and commit                                                                git status          # Review changes
git add <files>     # Stage specific files
git commit -m "Clear message describing what and why"                           Push to remote                                                                  git push                                                                        git checkout -b feature/feature-name                                            git checkout main
git merge feature/feature-name
git push                                                                        git branch -d feature/feature-name                                              git log             # View commit history
git log --oneline   # Compact view
git diff            # See unstaged changes
git show <commit>   # View specific commit                                      git log             # View commit history
git log --oneline   # Compact view
git diff            # See unstaged changes
git show <commit>   # View specific commit                                      git log             # View commit history
git log --oneline   # Compact view
git diff            # See unstaged changes
git show <commit>   # View specific commit                                                                                                                      # Undo last commit (keep changes)
git reset --soft HEAD~1

# Discard all local changes
git reset --hard HEAD

# View file history
git log -- <filename>

# Blame (see who changed what)
