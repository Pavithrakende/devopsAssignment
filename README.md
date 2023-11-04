commands used:

git init

git remote add origin "https://github.com/Pavithrakende/devopsAssignment.git"

notepad sample.txt

git add .

git commit -m "first commit in master"

git push origin master

git branch feature-branch

git checkout feature-branch

notepad sample.txt

git add .

git commit -m "first commit in feature-branch"

git push origin feature-branch

git checkout master

git merge feature-branch

git push origin master