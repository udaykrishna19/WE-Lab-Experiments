#…or create a new repository on the command line
  -> echo "# WE-Lab-Experiments" >> README.md
  -> git init
  -> git add README.md
  -> git commit -m "first commit"
  -> git branch -M main
  -> git remote add origin https://github.com/udaykrishna19/WE-Lab-Experiments.git
  -> git push -u origin main

#…or push an existing repository from the command line
  -> git remote add origin https://github.com/udaykrishna19/WE-Lab-Experiments.git
  -> git branch -M main
  -> git push -u origin main

git add .
git commit -m "Added new files"
git push origin main

git push --set-upstream origin main
