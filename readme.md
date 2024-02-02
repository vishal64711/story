git init 

git add chapter1.txt
//adds to staging area

git commit -m "Complete Chapter 1"
// add to local git repository

git status

git add .

git commit -m "complete chapter 2 and 3"

git diff chapter3.txt

git checkout chapter3.txt

-------------------------Github and Remote Repo----------

git remote add origin https://github.com/Angela
git push -u origin main 

---------------------Gitignore---------------------------
touch .gitignore

git rm --cached -r .

