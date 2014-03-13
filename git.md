Git Instructions
================

Initialize Git: 
git init

Add File: 
git add README.md
git commit -m "first commit"

Add everything:
git add *
git commit -m "Added Everything"

Remove File:
git rm --cached <file>

or

git rm <file>
git commit -m "Removing a file"

Remove Orgin:
git remote rm origin

Add Orgin:
git remote add origin https://github.com/emaad-shah/repo.git

Set Orgin:
git remote set-url origin "https://..." 

Push Files to Github:
git push -u origin master

Pull Files from Github:
git pull -u origin master

Check current Origin
git remote -v
