
STEPS USED

create a new repository on the command line
echo "# RestAPI" >> README.md
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/YesInAJiffy/RestAPI.git
git push -u origin main



==========================================================================
echo .DS_Store >> ~/.gitignore
+++++++++++++++++++++++++++++++++++

BELOW IS JUST FOR READING

https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github


Adding a local repository to GitHub using Git

Create a new repository on GitHub.com. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub. For more information, see "Creating a new repository."

At the top of your repository on GitHub.com's Quick Setup page, click  to copy the remote repository URL.

Screenshot of the "Quick Setup" header in a repository. Next to the remote URL, an icon of two overlapping squares is highlighted with an orange outline.

Open Terminal.

Change the current working directory to your local project.

Add the URL for the remote repository where your local repository will be pushed.

$ git remote add origin <REMOTE_URL>
# Sets the new remote
$ git remote -v
# Verifies the new remote URL
Push the changes in your local repository to GitHub.com.

$ git push -u origin main
# Pushes the changes in your local repository up to the remote repository you specified as the origin
