<h1> 👨🏾‍💻 GIT ANNOTATIONS </H1>
<h2> Useful Git Commands </h2>

>⚠️ status: developing

#### Git Downloading<br>
+ https://git-scm.com/download

#### Checking Git installed version<br>
+ git --version

#### Creating/Initializing an empty repository/default branch<br>
+ git init

#### Changing default branch name from "master" to "main"<br>
+ git branch -M "main"<br>

#### Showing the repository status<br>
+ git status

#### Adding file to stage<br>
+ git add fileName

#### Adding all available files to stage<br>
+ git add .

#### Creating a commit<br>
+ git commit -m "shortCommitDescription"

#### Creating a repository at GitHub<br>
+ https://github.com

#### Adding/Connecting a remote sync between the Git and a Github repository<br>
+ git remote add origin "repository-URL"

#### Pushing the local repository to the remote repository<br>
+ git push -u origin main

#### Pulling the remote repository changes<br>
+ git pull

#### Cloning a Git Hub Repository<br>
+ git clone repositoryURL

#### Creating a new branch<br>
+ git checkout -b Secbranch

#### Switching branches<br>
+ git checkout main

#### Merging branches<br>
+ git merge branchName

#### Aborting merged branches<br>
+ git merge --abort

#### Deleting a local branch<br>
+ git branch -d branchName

#### Deleting a remote branch<br>
+ git push origin :branchName

#### Refreshing GitHub:
<table>
    <tr>
        <td>1st- Save file changes</td>
    </tr>
    <tr>
        <td>2nd- git add .</td>
    </tr>
    <tr>
        <td>3rd- git commit -m "shortCommitDescription"</td>
    </tr>
    <tr>
        <td>4th- git push origin branchName</td>
    </tr>
 </table>
