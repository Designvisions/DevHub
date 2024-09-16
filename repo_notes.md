# Clone the repository
git clone https://github.com/username/repo-name.git
cd repo-name

# Create directories and files
mkdir JavaScript Python
touch README.md

# Stage and commit changes
git add .
git commit -m "Initial commit"

# Push changes to GitHub
git push origin main

# Create and switch branches
git checkout -b new-feature

# Push a branch
git push origin new-feature

# Merge and delete branch (after PR)
git checkout main
git merge new-feature
git branch -d new-feature
git push origin --delete new-feature

# Pull latest changes
git pull origin main

# Check repository status
git status

# View commit history
git log
