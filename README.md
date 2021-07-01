#Welcome to the Git Demo#

This is a cheat sheet covering all the basic Git commands

GIT Version Control

Benefits of Source Control
1. Versioning of Files
2. Improved Development Process
3. Historical View
4. Work with Team

#git init                      *when inside the folder you want to intitialize
#git init [repository name]
#git clone                      

#notepad README.md             *creates notepad readme

#git status 
-details modifications, what has been staged, untracked files

#git add [file name]          *adds specific file to staging
#git add .                    *adds everything to staging
#git add --all                *adds deleted files to staging

#git commit 
#git commit -m "[message]"     *commits staged changes 

#git branch                    *displays all branches and tells you the current branch you are working on

#git branch [branch name]      *creates new branch
#git checkout -b [branch name] *also creates new branch, and switches you to that branch

#git checkout [branch name]    *swithces to branch name

#ls                            *displays all files within current directory

                              *git tracks files, not folders.

#git branch -d [branch name]   *deletes branch
#git branch -D [bramch name]   *if branches have not been merged

*do all your work on a seperate branch, then merge that work into the master branch

*you can merge a branch from master branch or merge master from the branch you are working in.
* it is better to merge the master branch into the branch you are working in.
* this way if you make a mistake, your master branch is not corrupted. 

#git merge [branch name] *merges branches. only relevant if the [branch name] has changed. 

*a 'remote' is a repository that lives somewhere else. The repos can even be on the same machine.
* a 'remote' can also live on a website such as GitHub or BitBucket

#git remote add origin [url]
(*origin is just a name that identifies the remote, you could name it anything)
(*origin is a convention for the main repo that everyone points to)

#git remote
* displays remote/s

#git push -u origin master
*pushes current master branch up to the origin remote branch
* -u allows us to track the changes on the remote repo


