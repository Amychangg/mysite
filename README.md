echo "# mysite" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Amychangg/mysite.git
git push -u origin main


git branch -m master base
git fetch origin
git branch -u origin/base base
git remote set-head origin -a