1. Create repo with 'git init' in local folder.
2. Add file to commit with 'git add <filename>' or 'git add .' to add all content in folder.
3. Commit changes with 'git commit -m "init"'.
4. Create a new repo on GitHub.
5. Do 'git remote add origin https://github.com/<GitHub_username>/<repository_name>.git'.
6. Push changes with 'git push -u origin <branchname>' where branchname can be main or master.
7. Create development branch with 'git checkout -b development'.
8. Add updated README.md to commit with 'git add README.md'.
9. Commit changes with 'git commit -m "Add instructions to README.md"'.
10. Switch to master branch and merge with development with 'git checkout master' and 'git merge development'.
11. Check status with 'git status', commit and push changes.

