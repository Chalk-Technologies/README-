# README-
internal documentation

->Git management

   -Getting latest changes for master branch:
    first access the file repository the master branch you would like to access is on.
    
   for example:
    
    ...
    cd data-backend
    ...
   then
   
    ...
    git pull origin master
    ...
   To check if you are up to date
    
    ...
    git status 
    ...
   It will output "your branch is up to date with origin/master"
   
  -Checkout of a new branch
    Once new branch is created, using 'git branch', 
    one can switch to it by using:
    
     ...
     git checkout
     ...
    
  -Addition of descriptive commit messages
    
    On the command line navigate to the repository that contains the commit you want to amend. Type git commit --amend and press Enter. In your text editor, edit the commit
    message, and save the commit.
    
   -Pushing branches
   
    ...
    git push -u origin master
    ...
    
   note- 'master' represents branch name.
   
  -When to create a pull request:
  
    After you create a branch and make changes to files in a project, you can create a pull request. With a pull request, you can propose, discuss, and iterate on changes before     you merge the changes into the project. You can create a pull request in your project's repository with GitHub Desktop.
