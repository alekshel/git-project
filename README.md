# Опис виконання

git init
git add .
git commot -m 'init project'

git checkout -b new_branch
git add .
git commit -m 'init new_branch'

git checkout master
git remote add origin git@github.com:alekshel/git-project.git
git push -u origin master