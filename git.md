# Delete Merged Branches (Local)

git fetch -p && git branch -vv | awk '/: gone]/{print $1}' | xargs git branch -D

# List and Edit Local Configs

git config --list --local
git config user.name "name"
git config user.email "email@example.com"

# List and Edit Global Configs

git config --list
git config --global user.name "name"
git config --global user.email "email@example.com"
