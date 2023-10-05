# GitGitHub
<br>
Git Configurations
<br>
<br>
1. To Remove the Account from the system
<br>
<br>
         Unset userName
 <br>
   -  git config --global --unset user.name
 <br>
         Unset userEmail
<br>
   -  git config --global --unset user.email
<br>
         Unset Creds
<br>
  -  git config --global --unset credential.helper
<br>
<br>
2. To permanently delete git from system
<br>
<br>
  -  cmdkey /delete:LegacyGeneric:target=git:https://github.com
  <br>
  <br>
3. To add new git account on system 
<br>
<br>
     Set userName
     <br>
  -   git config --global user.name "ByteBusters09"

<br>
Set userEmail
<br>
 -   git config --global user.email "xyz@gmail.com"
<br>
<br>
4. To permanently store password of github on system 
<br>
<br>
-  git config  credential.helper store
<br>
<br>
5 . To check the configurations
<br>
<br>
-  git config --list
<br>
[This will list out all the account with username and user email]
<br>
<br>
6. git config is used for the configuration of the git , and configurations can be done by two methods - 
   <br>
   . --global   [means globally on a system]
   <br>
   . --local    [means for a particular project we are using a diffrent account]
   <br>
<br>
7 . git clone
<br>
   -to copy the git project on local 
<br>
<br>
8 . Two types of locations 
<br>
   . local [laptop or pc]
<br>
   . remote [ github ]
<br>
<br>
9 . git status  - this command is used to display the state of code, whether any file is changed or not
<br>
    Generally, when we are using git status, we can find four types of status
<br>
   . Untracked files - these are the file that are added on local, but not yet tracked by git [ new files]
   <br>
   . Modified - these are the files which are already tracked by git, and its been modified/changed [ added some change in it] now
   <br>
   . Staged - the files that are ready to be commited
   <br>
   . Unmodified  - these are the files that are not modified
   <br>
<br>
10. git add .   -this command is used to add the changes that are done on files [to add all files we use this command]. Adding a file makes it staged.
<br>
<br>
11. git add <fileName> - this command is use to add single file at a time.
<br>
<br>
12 . ls -a  - this command is used to list down all the files including hidden files
<br>
<br>
13 .  git commit -m "message"    - this command is used to save the changes or takes the screenshots preceded by a message, that what actual change was done in the file
<br>
<br>
14. git push   - this command is use to push all the changes to remote, once added and commited. or simply this command is used to upload local repo content to remote repo
<br>
<br>
15.  git push origin main - this command is used when we have only one branch that is main ,here origin is a repository on github which we have cloned and started working.
<br>
<br>



# To use git in local, commands used are :
# with help of these commands we can directly make repos on git

<br>
1. git init - this command is use to initialize a new git repository
<br>
2. mkdir <DirectoryName> - this command is used to make a new directory/folder/repository
<br>
3. ls -a    - by this command we can check, if our git repository is initialized or not, using this command gives us a .git folder.
         <br>
4. git status
<br>
5. git add .
<br>
6. git commit -m "message"
<br>
<br>

#To upload our local project on github 
<br>
1. go to github account
 <br>
2. goto settings
    <br>
3. goto Repositories
   <br>
4. create a new repo with a suitable name
   <br>
5. create a new repo
   <br>
6. on local
 <br>
use commands
<br>
git remote add origin <link that was popped while creating a new repo> - origin is set on local
<br>
7 . git remote -v   - we will use this command to verify the remote
   <br>
8. git branch - this will show on which branch we are currently working
   <br>
9. git branch -M <branchName>  - to rename the existing branch
    <br>
10. git push -u origin main     ---- -u means upstream
    <br>
11. refresh on github will display the local changes in it.
    <br>
12. we can simply create a new README.md file on local as well
    <br>
13. git add .
    <br>
14. git commit -m "message"
    <br>
15 . git push
    <br>
    <br>

    # BRANCH COMMANDS
    <br>
1. git branch - this command will display the current branch that we are working on.
   <br>
2. git checkout -b <branchName> - with the help of thois command we will create a new branch .
   <br>
3 . git checkout <branchName> - with the help of this command we navigate through branches.
   <br>
4. git branch -d <branchName> - with the help of this command we delete the branch.
   <br>
  <br>
5.
