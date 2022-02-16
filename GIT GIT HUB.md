Git/Windows10 64 bits;
https://git-scm.com/download/win

Cloning a Git Hub Repository
git clone repositoryURL

Checking Git installed version;
git --version

Creating/Initializing an empty repository/default branch;
git init

Changing default branch name from "master" to "main";
git branch -M "main"

Showing the repository status;
git status

Adding file to stage;
git add fileName

Adding all available files to stage;
git add .

Creating a commit;
git commit -m "shortCommitDescription"

Creating a repository at GitHub;
https://github.com

Adding/Connecting a remote sync between the Git and a Github repository;
git remote add origin "repository-URL"

Pushing the local repository to the remote repository;
git push -u origin main

Creating a new branch;
git checkout -b Secbranch

Switching branches;
git checkout main

Merging branches;
git merge branchName

Aborting merged branches;
git merge --abort

Deleting a local branch;
git branch -d branchName

Deleting a remote branch;
git push origin :branchName

Refreshing GitHub:
1st- Save file changes
2nd- git add .
3rd- git commit -m "shortCommitDescription"
4th- git push origin branchName