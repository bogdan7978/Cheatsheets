> Connotations '--' are reffered to as flag\

### Info
`git --version`\
`git init` - **Initialize git in a directory**\
`git config --list` (':q' to quit the screen) - **Used to identify users**\
`git config --global user.name "name"`\
`git config --global user.email "email"` - **Create a new user**\
`git status` - **Check the changes to the repo**

>In VScode go to `settings` --> search for `files.ex` and remove `.git` to show the **git** directory

> Remove the `.git` to un-initialize **git** from your project


**create a `.gitingnore` file and add the files you want to hide**

`git restore <filename>` - **Restore the changes made to a file**\
`git add .` - **Add all the changed files**\
`git reset .` - **Return all the files to untracked/staged (undo git add)**\
`git commit -m "message"` - **Add a snapshot of your changes**\
`git log` - **See a history of the commits**\
`git commit -am "message"` - **Commit without using git add**\
`--dry-run` - **Test a commit**\
`git commit --amend "new message"` - **Change the message of a commit**

`git remote` - **Rells you which remote repositories are linked to your local one**\
`git remote add origin <url-to-repository>` - **Link a remote repository**\
`git remote -v` - **Show details about remote repository**\
`git remote show origin` - **More details about remote repository linked**

```
git push origin(name of remote repo) master(branch you want) -u(set origin to upstream remote, when you pull you need no arguments)
```

### Sync changes from remote repo to local one
`git fetch` - **Download latest changes**\
`git merge origin/master` - **Merge the two braches (remote and local)**\
`git pull` - **Alternative to fetch and merge**\
```
git clone <url> <folder>(optional, if specified it will create a new folder)
```
### Branches
`git branch` - **Check the branches of a repo**\
`git branch -M <name>` - **Rename master branch to main**\
`git branch <name>` - **Create a new branch**\
`git branch -d` - **Delete a branch (use -D to fore delete)**\
`git checkout <name>` - **Switch branches**\
`git checkout -b <name>` - **Create a new branch and switch to it**\
`git checkout -` - **Takes you to previous branch**

### Merging
> Merge conflicts - When branches modified the same line of code (and commited the changes)

`git merge <branch-name>` - **The branch using this command will take the changes of the other branch specified**\
`git diff` - **To see the conflict**\
`git merge --abort` - **Cancel the merge**\
> After a merge conflict is resolved, an `add and commit` command is needed to save the changes

>A fork is created when you want to work on a project from GitHub on your own account. After that a pull request is sent to the original author and reviewed.