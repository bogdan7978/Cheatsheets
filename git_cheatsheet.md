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
git commit -a -m "message" - to commit without using git add
--dry-run - to test a commit

git remote - tells you which remote repositories are linked to your local one
git remote add origin <url-to-repository> - to link a remote repository
git remote -v - to show details about remote repository
git remote show origin - more details about remote repository linked

git push origin(name of remote repo) master(branch you want) -u(set origin to upstream remote, when you pull you need no arguments)