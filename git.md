# Delete Merged Branches (Local)

git fetch -p && git branch -vv | awk '/: gone]/{print $1}' | xargs git branch -D

# Local Configs

git config --list --local

git config user.name "kaiclairvoyant"

git config user.email "kai.example@hotmail.com"

# Global Configs

git config --list

git config --global user.name "kaiclairvoyant"

git config --global user.email "kai.example@hotmail.com"
