Conotations -- = flag
git --version
git config --list (':q' to quit the screen) - Used to identify users
git config --global user.name "name"
git config --global user.email "email" --to create a new user
git init - to initialize git in a directory
VScode go to setting -> search for 'files.ex' and remove .git to show the git directory
remove the .git to un-initialize git from your project
git status to check the changes to the repo
create a .gitingnore file and add the files you want to hide
git restore <filename> - to restore the changes made to a file
git add . - to add all the changed files
git reset . - to return all the files to untracked/staged (undo git add)
git commit -m "message" - To add a snapshot of your changes
git log - to see a history of the commits
git commit -am "message" - to commit without using git add
--dry-run - to test a commit

git remote - tells you which remote repositories are linked to your local one
git remote add origin <url-to-repository> - to link a remote repository
git remote -v - to show details about remote repository
git remote show origin - more details about remote repository linked

git push origin(name of remote repo) master(branch you want) -u(set origin to upstream remote, when you pull you need no arguments)

Sync changes from remote repo to local one
git fetch - to download latest changes
git merge origin/master - to merge the two braches (remote and local)
git pull - alternative to fetch and merge

git clone <url> <folder>(optional, if specified it will create a new folder)

git branch - to check the branches of a repo
git branch -M <name> - rename master branch to main
git branch <name> - to create a new branch
git branch -d - to delete a branch (use -D to fore delete)
git checkout <name> - to switch branches
git checkout -b <name> - to create a new branch and switch to it
git checkout - - takes you to previous branch

git merge <branch-name> - The branch using this command will take the changes of the other branch specified
Merge conflicts - When branches modified the same line of code (and commited the changes)
git diff - to see the conflict
git merge --abort - to cancel the merge
After a merge conflict is resolved, an 'add and commit' command is needed to save the changes

A fork is created when you want to work on a project from GitHub on your own account. 
After that a pull request is sent to the original author and reviewed.

git commit --amend "new message" - To change the message of a commit