# git-commands

This repo is to test the git commands

## Fork 
Copy the complete repo to my account 
That can I change any thing in the repo local

# git
## git init
Create an initial repo

## git remote add origin [Repo-url]
Change the remote origin

## git clone [Repo-url]
Clone a repo local

## git config
git config --global user.email "example@email.com"
git confit --global user.name "Your Name"

## git remote set-url origin [SSH:Git]
Change the remote Repo

## git status
Show tracked and untraked files

## git add [file or . for all files]
Add changes to stage

## git commit -m "Title" -m "Description"
Commit changes from stages
-m is parameter for message
## git commit -am "Title"
Add and commit a CHANGED Files 

## git push -u origin [Branch]
Push changes to remote branch
-u is short parameter for --set-upstream

## git checkout -b 'Branch-Name'
Create a new Branch

## git checkout 'Branch-Name'
Change the Branch

## git pull
Pull changes from the remote branch

## git fetch
Fetch branches from remote

## git branch
Show branches

## git branch -d [Branch-Name]
Delete a Branch

## git merge [Branch-Target]
Merge a current branch to a target branch

## git reset [File-Name]
Delete the file from the stage

## git reset HEAD~[Index of Commit]
Reset to the last Commit

## git reset [Commit-Hash]
Reset to the specific Commit

## git reset --hard [Commit-Hash]
Reset to the specific Commit not only unstaged but to be completly removed

