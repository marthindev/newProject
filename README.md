# newProject

for first - push from local to github - create new repo in github same name in local: newProject
then in local newProject folder terminal run below

…or create a new repository on the command line
echo "# new" >> README.md
git init
git add README.md
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/marthindev/newProject.git
git push -u origin main

for first time - git push will do Authorize Git Credential Manager with github browser


After connected /sync local git working dir / folder with github - to push new update to github run :
git add README.md
git commit -m "commit"
git push -u origin main

git status