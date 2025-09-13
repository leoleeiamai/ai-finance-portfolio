# ai-finance-portfolio
This repo shows my journey combining equity research + AI/ML for UK buy-side roles.

git config --global user.name "Leo Lee"
git config --global user.email "leolee.iamai@gmail.com"

mkdir ai-finance-portfolio
cd ai-finance-portfolio
git init -b main
: > README.md  

git add README.md
git commit -m "chore: add blank README"
git remote add origin https://github.com/<your-username>/ai-finance-portfolio.git
git push -u origin main

printf "This repo shows my journey combining equity research + AI/ML for UK buy-side roles.\n" > README.md
git add README.md
git commit -m "docs: add project description to README"
git push



# .gitignore for Python
curl -s https://raw.githubusercontent.com/github/gitignore/main/Python.gitignore -o .gitignore
git add .gitignore
git commit -m "chore: add Python .gitignore"
git push

# MIT License template (optional)
curl -s https://raw.githubusercontent.com/github/choosealicense.com/gh-pages/_licenses/mit.txt -o LICENSE
git add LICENSE
git commit -m "chore: add MIT License"
git push
