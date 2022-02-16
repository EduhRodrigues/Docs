<h1> GIT ANNOTATIONS </H1>
<h2> Useful Git Commands </h2>

>status: Developing

<h5>Git/Windows10 64 bits</h5>
<h6>https://git-scm.com/download/win</h6>

Cloning a Git Hub Repository<br>
git clone repositoryURL

Checking Git installed version<br>
git --version

Creating/Initializing an empty repository/default branch<br>
git init

Changing default branch name from "master" to "main"<br>
git branch -M "main"<br>

Showing the repository status<br>
git status

Adding file to stage<br>
git add fileName

Adding all available files to stage<br>
git add .

Creating a commit<br>
git commit -m "shortCommitDescription"

Creating a repository at GitHub<br>
https://github.com

Adding/Connecting a remote sync between the Git and a Github repository<br>
git remote add origin "repository-URL"

Pushing the local repository to the remote repository<br>
git push -u origin main

Creating a new branch<br>
git checkout -b Secbranch

Switching branches<br>
git checkout main

Merging branches<br>
git merge branchName

Aborting merged branches;
git merge --abort

Deleting a local branch;
git branch -d branchName

Deleting a remote branch;
git push origin :branchName

<h3> Refreshing GitHub: </h3><br>
<h4>1st- Save file changes<br>
    2nd- git add . <br>
    3rd- git commit -m "shortCommitDescription" <br>
    4th- git push origin branchName
</h4>
