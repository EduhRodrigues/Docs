# ![icons8-git](https://user-images.githubusercontent.com/67625804/154203860-ac702c40-98c9-4bab-a3f5-c93b97f46980.svg) GIT ANNOTATIONS
###### ⚠️  status: Developing <br> <br>
 
 
### ``` Useful Git commands: ```


  <dt>Git Downloading</dt>
  
 **``` https://git-scm.com/download ```**
   
  <dt>Checking Git installed version:</dt>
  
  **``` git --version ```**
 
  <dt>Creating/Initializing an empty repository/default branch:</dt>

  **``` git init ```**
 
<dt>Changing default branch name from master to main:</dt>

  **``` git branch -M "main" ```**
 
 <dt>Showing the repository status:</dt>
 
 **``` git status ```**
 
 <dt>Adding file to stage:</dt>
 
  **``` git add fileName ```**
 
 <dt>Adding all available files to stage:</dt>
 
  **``` git add . ```**
 
 <dt>Creating a commit:</dt>
 
  **``` git commit -m "shortCommitDescription" ```**
 
 <dt>Creating a repository at GitHub:</dt>
 
  **``` https://github.com ```**
 
 <dt>Adding/Connecting a remote sync between the Git and a Github repository:</dt>
 
  **``` git remote add origin "repository-URL" ```**

  <dt>Deleting a remote sync between the Git and a Github repository:</dt>
 
  **``` git remote remove origin ```**

   <dt>Setting up origin main:</dt>
 
  **``` git push --set-upstream origin main ```** 

 
 <dt>Pushing the local repository to the remote repository:</dt>
 
  **``` git push -u origin main ```**
 
 <dt>Pulling the remote repository changes:</dt>
 
  **``` git pull ```**
 
 <dt>Cloning a Git Hub repository:</dt>
 
  **``` git clone repositoryURL ```**
 
 <dt>Creating a new branch:</dt>
 
 **``` git checkout -b feature ```**
 
 <dt>Switching branches:</dt>
 
  **``` git checkout main ```**
 
 <dt>Merging branches:</dt>
 
  **``` git merge branchName ```**
 
 <dt>Aborting branches merging:</dt>
 
  **``` git merge --abort ```**
 
 <dt>Deleting a local branch:</dt>
 
  **``` git branch -d branchName ```**
 
 <dt>Deleting a remote branch:</dt>
 
  **``` git push origin :branchName ```**
<br>
<br>
<dt> Update in Github remote directory: </dt>

**``` 1st Save the file changes ```**

**``` 2nd git add . ```** 

**``` 3rd git commit -m "shortCommitDescription" ```**

**``` 4th git push origin branchName ```**
<br>
<br>
<dt> Update in local directory: </dt>

**``` 1st Commit changes in the remote directory ```**

**``` 2nd git pull```** 
