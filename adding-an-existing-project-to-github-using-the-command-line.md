#adding-an-existing-project-to-github-using-the-command-line 
*Create a new repository on GitHub. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub.*
- git init
- git add .
- git commit -m "First commit"
*Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.*
- git remote add origin ${remote repository URL}
*Sets the new remote*
- git remote -v
*Verifies the new remote URL*
- git push -u origin master
*Pushes the changes in your local repository up to the remote repository you specified as the origin*
*refer from https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line*
