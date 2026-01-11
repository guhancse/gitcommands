**Basic commands**

git init 

git config user.name "Guhan Shankar"

git remote add origin https://guhanDEVOPS@dev.azure.com/guhanDEVOPS/DOTNETFramework/_git/DOTNETFramework

git remote -v

git add . (Staging)   | git add index.html

git commit -m "First Commit"

git push origin master

$ git checkout <existing_branch>

$ git checkout -b <new_branch>

git clone https://guhanDEVOPS@dev.azure.com/guhanDEVOPS/DOTNETFramework/_git/DOTNETFramework

git log (View List of commit history)

git hook (.git/hooks) (validation)

git tag (version number for your release) ex: git tag v1.0

git reset

git stash (temporary hide your changes)

  git stash pop
  git stash list


**Merge a particular commit into a branch**

git cherry-pick commitID (merge a particular commit into a branch)

