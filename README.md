How to push changes to GitHub from an existing repository (without having to use git clone)

push an existing repository from the command line:

git remote add origin https://github.com/CDDR1/RepositoryName.git
git branch -M main
git push -u origin main
