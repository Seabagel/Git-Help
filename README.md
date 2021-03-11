# Git Help
 Links to Git resources, and common commands

Commit changes, -all bypass staging, -message "github", then push to remote repository
git commit -a -m "github"
git push

Fetch the remote repository's current state
git fetch

Update the current repository to remote's state
git pull

Make a new file
echo "# <repository_name>"

create a new repository on the command line
echo "# <repository_name>" > README.md
git init
git add README.md
git commit -m "<message>"
git branch -M <initial_branch_name>
git remote add origin https://github.com/Seabagel/<repository_name>.git
git push -u origin <initial_branch_name>

push an existing repository from the command line
git remote add origin https://github.com/Seabagel/<repository_name>.git
git branch -M <initial_branch_name>
git push -u origin <initial_branch_name>

https://www.atlassian.com/git/tutorials/using-branches/git-checkout

Change and Make branches
git checkout <existing_branch>
git checkout -b <new_branch>

Push Branch To Remote
https://devconnected.com/how-to-push-git-branch-to-remote/
List branches
git branch

git push <remote> <branch>
git push origin <branch>

git Switch
https://bluecast.tech/blog/git-switch-branch/

git set password
https://stackoverflow.com/questions/35942754/how-to-save-username-and-password-in-git
git config --global credential.helper cache

Update git link after changing Repository name
https://stackoverflow.com/questions/30443333/error-with-renamed-repo-in-github-remote-this-repository-moved-please-use-th

Removing non-repository files with git?
https://stackoverflow.com/questions/5037480/removing-non-repository-files-with-git

Merging local branch
https://barbagroup.github.io/essential_skills_RRC/git/branching/#:~:text=To%20do%20a%20merge%20(locally,you%20want%20to%20merge%20FROM.&text=Because%20the%20history%20of%20master,%22fast%2Dforward%22%20merge.
We are on the master branch and want to merge in make_function so we do:
$ git merge make_function 