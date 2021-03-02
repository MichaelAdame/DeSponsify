echo "# DeSponsify" >> README.md
git init
git add README.md
mkdir docs
touch docs/.gitignore
git add docs/.gitignore
git commit -m "first commit"
git remote add origin git@github.com:MichaelAdame/DeSponsify.git
git push -u origin master
