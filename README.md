GIT Version Control

Goals of Source Control
1. Versioning of Files
2. Improved Development Process
3. Historical View
4. Work with Team

git init (when inside the folder you want to intitialize)
git init [repository name]
git clone

notepad README.md -creates notepad readme

git status 
-details modifications, what has been staged, untracked files

git add [file name]          
  *adds specific file to staging

git add .                    
  *adds everything to staging

git add --all                
  *adds deleted files to staging

git commit 
git commit -m "[message]"
  *finalizes changes added to the staging area

git branch                   
 *displays all branches and tells you the current branch you are working on

git branch [branch name]      
 *creates new branch

git checkout -b [branch name] 
 *also creates new branch, and switches you to that branch

git checkout [branch name]    
  *swithces to branch name

ls                            
  *displays all files within current directory
  *git tracks files, not folders.

git branch -d [branch name]   
  *deletes branch

git branch -D [branch name]   
  *if branches have not been merged

*do all your work on a seperate branch, then merge that work into the master branch

* You can merge a branch from master branch or merge master from the branch you are working in.
* It is better to merge the master branch into the branch you are working in,
* this way if you make a mistake, your master branch is not corrupted. 

git merge [branch name] 
  *merges branches. only relevant if the [branch name] has changed. 

*a 'remote' is a repository that lives somewhere else. The repos can even be on the same machine.
* a 'remote' can also live on a website such as GitHub or BitBucket

git remote add origin [url]
  *origin is just a name that identifies the remote, you could name it anything.
  *origin is a convention for the main repo that everyone points to.

git remote
  *displays remote/s

git push -u origin master
  *pushes current master branch up to the origin remote branch
  * -u allows us to track the changes on the remote repo

git push origin master
  *for all subsequent changes to remote branch
  
  git fetch
  *pulls down all of the branches from the remote repository
  *you can only merge from the branches fetched from a remote repo. You cannot change them directly. 

git pull [alias] [branch]
  *pulls down the branch being requested and merges it with your current branch.
  *essentially a 'git fetch' and 'git merge' in one step. 



