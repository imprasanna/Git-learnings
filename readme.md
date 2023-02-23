Check the version of github:
git --version

List the files in the current working directory:
ls

Show even hidden file:
ls -la

Change the working directory:
cd folder-name

Remove that additional file from staging area:
git rm --cached filename.ext

Remove that additional file from the secondary memory:
git rm waste.html

Check git status:
git status

Add git file to staging environment:
git add index.html

Add more than one file or all files to staging environment
git add index.html style.css
git add --all
git add .

Check status of the repo in a more compact way:
git status --short
or, git status -s

Commit the change with message:
git commit -m "First release of Hello World!"

Note: Short status flags are:
?? - Untracked files
A - Files added to stage
M - Modified files
D - Deleted files

Git commit without stage for already tracked file:
git commit -a -m "Updated index.html with a new line"

View the history of commits for a repository
git log
git show
git log --oneline (in one line)

See all the available options for the specific command:
git command --help

See all possible commands:
git help --all

Note: If you find yourself stuck in the list view,
SHIFT + G to jump the end of the list,
then q to exit the view.

Create a new branch:
git branch branch-name

Check and confirm which branch you are on:
git branch

Move from the current branch to another branch:
git checkout branch-name

Note: Now, check the status of the current branch

Note: Then, add the branched file to the staging environment
and also commit

List all the files in the current directory:
ls

Change from current branch to master
git checkout master

Directly create and shift to a new branch:
git checkout -b new-branch

Merge a branch to master:
git merge branch-name

Delete a branch:
git branch -d branch-name

Push local repository to GitHub:
git remote add origin repo_url

Push master branch to local origin:
git push -u origin master

Pull the file to local after merge:
git pull

Clear screen:
Ctrl + L
or, type => clear

Quit from a running process:
Ctrl + C

Commit:
git commit -m "First file"

Config:
git config --global user.email "prasannaacharya2073@gmail.com"
git config --global user.name "Prasanna Acharya"
git conig --list

Delete recent commits:
git reset [unique_commit_id]
(View commit-id using => git log or, => git log --oneline)

Edit the commit message of the recent commit:
git commit --amend -m "New commit message"

Other commands:
git push origin -f
(This will force)

git remote --verbose
