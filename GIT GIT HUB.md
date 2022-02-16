Git/Windows10 64 bits;
https://git-scm.com/download/win

Cloning a Git Hub Repository
git clone repositoryURL


Checking Git installed version;
git --version

Creating/Initializing an empty repository/default branch;
git init

Showing the repository status;
git status

Adding the readme.md file to stage;
git add readme.md

Adding all available file to stage;
git add .

Creating a commit;
git commit -m "Nota da versão"

Creating a GitHub repository;
https://github.com

Adding/connecting a remote sync between Git to Github;
git remote add origin "repository-URL"

Pushing the local repository to the remote repository;
git push -u origin main

Changing default branch name from "master" to "main";
git branch -M "main"

Creating a new branch;
git checkout -b Secbranch

Switching branches;
git checkout main

Merging branches;
git merge Secbranch

Aborting merged branches;
git merge --abort

Deleting a local branch;
git branch -d Secbranch

Deleting a remote branch;
git push origin :Secbranch

Refreshing GitHub:
1- Save file changes
2- git add .
3- git commit -m "blabla"
4- git push origin mainHighlights

What I learned about Versioning (Git/GitHub)

Instaling Git/Windows10 64 bits;
https://git-scm.com/download/win

Checking Git installed version;
git --version

Creating/Initializing an empty repository/default branch;
git init

Showing the repository status;
git status

Adding the readme.md file to stage;
git add readme.md

Adding all available file to stage;
git add .

Creating a commit;
git commit -m "Nota da versão"

Creating a GitHub repository;
https://github.com

Adding/connecting a remote sync between Git to Github;
git remote add origin "https://github.com/EduhRodrigues/Git_Apprenticeship.git"

Pushing the local repository to the remote repository;
git push -u origin main

Logging the personal Github account;
https://github.com

Changing default branch name from "master" to "main";
git branch -M "main"

Creating a new branch;
git checkout -b Secbranch

Switching branches;
git checkout main

Merging branches;
git merge Secbranch

Aborting merged branches;
git merge --abort

Deleting a local branch;
git branch -d Secbranch

Deleting a remote branch;
git push origin :Secbranch

Refreshing GitHub:
1- Save file changes
2- git add .
3- git commit -m "commit-name"
4- git push origin main