# Git Commands Quick Reference

## Daily Workflow
```bash
# Start of work session - always do this first
git fetch                  # Get latest info from GitHub
git status                 # Check if you have any local changes
git pull                   # Get latest changes from GitHub

# While working
git add .                  # Stage all your changes
git commit -m "Message"    # Save your changes with a description
git push                   # Send your changes to GitHub

```

## Useful Commands
```bash
# Check repository status
git status                 # See what files are changed/staged

# View remote connections
git remote -v             # See where your repo connects to

# Discard changes to a file
git restore filename.html  # Undo changes in a file

# Check branch name
git branch                # See which branch you're on
```

## Tips to Avoid Problems
1. Always PULL before starting new work
2. Commit your changes regularly with clear messages
3. Push your work before switching computers
4. If you get stuck, check `git status` first

## VS Code Integration
- Blue numbers in VS Code = uncommitted changes
- Source Control tab (Ctrl+Shift+G) shows changes
- Always review your changes before committing

Need help? Ask your instructor or refer to [GitHub's documentation](https://docs.github.com/en/get-started)