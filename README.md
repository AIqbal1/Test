# Git Commands

Merging upstream changes into your local repository is a common task in Git-based collaboration workflows. We already know how to do this with git fetch followed by git merge, but git pull rolls this into a single command.

Usage
git pull <remote>
Fetch the specified remote’s copy of the current branch and immediately merge it into the local copy. This is the same as git fetch <remote> followed by git merge origin/<current-branch>.

git pull remote@github/test/test

https://www.atlassian.com/git/tutorials/syncing/git-push


…or create a new repository on the command line

echo # f >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:AIqbal1/f.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin git@github.com:AIqbal1/f.git
git push -u origin master


example of git url

git@github.com:AIqbal1/f.git
