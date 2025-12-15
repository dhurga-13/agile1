# agile1
# Step 1: Initialize Git repository (only if not already done)

git init

# Step 2: Check the current status of the repository

git status

# Step 3: Add all Java source files to staging

git add \*.java

# Step 4: Add README.md if modified

git add README.md

# Step 5: Commit staged changes with a descriptive message

git commit -m "Add latest Java programs and update README"

# Step 6: Create or update .gitignore to ignore compiled class files

# This prevents pushing .class files to GitHub

echo \*.class > .gitignore
git add .gitignore
git commit -m "Add .gitignore to ignore .class files"

# Step 7: Add remote repository if not already added

git remote add origin https://github.com/dhurga145/agile1.git

# Step 8: If remote origin exists but needs update

git remote set-url origin https://github.com/dhurga145/agile1.git

# Step 9: Push all commits to GitHub (main branch)

git push -u origin main

# Step 10: Verify remote repository URLs

git remote -v

# Step 11: Final status check

git status



